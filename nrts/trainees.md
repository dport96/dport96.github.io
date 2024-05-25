---
layout: nrt
type: nrt
title: "Trainee Advising"
# All dates must be YYYY-MM-DD format!
date:
published: true
labels:
  - Advising
---
<div id="trainee_advising" class="container"></div>


<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
<script type="text/javascript">

google.charts.load('current', {'packages':['corechart']});
google.charts.setOnLoadCallback(querySheet);

function querySheet() {
    var queryString = encodeURIComponent(`SELECT B, D, E WHERE D = "{{ site.data.bio.basics.name }}" OR E = "{{ site.data.bio.basics.name }}"`);
    var query = new google.visualization.Query(
        `https://docs.google.com/spreadsheets/d/1cYoC5aqpM6r2DceIvGN8y0H5AK1b-n1CC-yX-NmWUtI/gviz/tq?sheet=Training&tq=${queryString}`
        );
    
    query.send(handleQueryResponse);
}

function handleQueryResponse(response) {
    if (response.isError()) {
        console.log('Error in query: ' + response.getMessage() + ' ' + response.getDetailedMessage());
        return;
    }

      var data = response.getDataTable();
      var numRows = data.getNumberOfRows();
      var results = [];

      for (var i = 0; i < numRows; i++) {
        var student = data.getValue(i, 0);
        var primaryAdvisor = data.getValue(i, 1);
        var secondaryAdvisor = data.getValue(i, 2);
        
        trainee_advising.innerHTML += 
`
<div class="card">
  <div class="card-body">
    <h5 class="card-title">${student}</h5>
    <p class="card-text">Primary Advisor: ${primaryAdvisor}</p>
    <p class="card-text">Secondary Advisor: ${secondaryAdvisor}</p>
  </div>
`;
        results.push({student: student, primaryAdvisor: primaryAdvisor, secondaryAdvisor: secondaryAdvisor });
      }
console.log(results);
}
</script>