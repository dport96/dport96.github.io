---
layout: project
type: project
image: img/WPP.jpeg
title: "Project: Work Pay Play Manager"
permalink: projects/WPP
# All dates must be YYYY-MM-DD format!
date: 2024-11-01
labels:
  - project
summary: 
---


### Overview

*The problem:* [The Work, Play, Pay Policy of Sail Kokokahi (SK)](https://sailkokokahi.com/policies) is designed to ensure that all members contribute to the club’s ongoing upkeep, social engagement, and [event](https://sailkokokahi.com/events) success through volunteer work. Each member is required to complete a minimum of 6 activity hours annually, with the club’s "work year" starting on December 1 and ending November 30 of the following year. Members have multiple options for fulfilling their hours:

- Work: Completing hours through approved activities such as maintenance projects, site improvements, or assisting with club clean-up days (1.5 hours per clean-up).

- Play: Volunteering at club events, such as attending or helping organize races, regattas, social activities, or other scheduled events (typically 1 hour per event).

- Pay: Any unfulfilled volunteer hours at the end of the policy period will be billed at $20 per hour and added to the member's following year’s renewal fee.

This policy encourages active participation in club activities while also offering a financial alternative to meet the hours requirement.

There are administrative challenges that arise from tracking, managing, and reporting volunteer hours requirement for members. Volunteer hours are manually tracked, which increases the risk of incomplete or inaccurate records. This inconsistency can lead to some members not fulfilling their commitment and others over-contributing without recognition.With no transparent system for members to monitor their own progress, there is less motivation to meet the required 6-hour volunteer commitment. This can result in an uneven distribution of work and may lead to burnout for the most active members. Members who do not meet the required hours must pay a fee. Manually calculating and billing these hours is time-consuming for administrators, especially if hours are logged incorrectly or retroactively. SK hosts events to foster community spirit, yet it is difficult to gauge engagement levels. Without a streamlined way for members to sign up and log participation, it’s challenging for SK to plan and improve future events.


*The solution:* A web application designed to help SK streamline, monitor, and manage volunteer hours contributed by its members. This application will enable members to self-register for credit, monitor their activity, and assist designated administrators in tracking and reporting members’ contributions and automating the billing process for unfulfilled volunteer hours. The app will enhance efficiency by providing members with easy access to their volunteer activity records, while ensuring compliance with SK’s community involvement requirements.

### Approach 

Instead of manual sign-ups for activities and spreadsheet generated reporting, the app will have:

**User Registration and Authentication**
- Members can register, log in, and access their individual profiles
- Authentication via email or membership ID to ensure secure access
- Role-based access control to distinguish between regular members and Directors or administrators

**Volunteer Hours Tracking**
- Members can log hours under designated categories such as:
  - Maintenance and Site Improvement
  - Clean-Up Days (1.5 hours per clean-up per member)
  - Social Events (1 hour for participation)
  - Club Racing Events (1 hour per event)
  - Event Organization (race, training session, etc.)
- Allow administrators to approve or edit entries, ensuring accuracy in recorded hours

**Dashboard and Reporting**
- A user dashboard displaying total hours contributed, pending hours, and categories of activities completed
- Admin dashboard with reporting features for tracking total hours by member and generating compliance reports

**Event Management**
- Calendar of upcoming volunteer events, including clean-up days, social gatherings, and races
- Sign-up functionality allowing members to indicate their participation in specific events
- Automatic reminders and alerts for upcoming events and unfulfilled volunteer hours

**Volunteer Hour Notifications**
- Automatic notifications to members as they approach the 6-hour requirement
- Monthly email summaries of hours contributed and outstanding obligations for each member

**Billing Module for Unfulfilled Hours**
- Calculate unfulfilled hours at the end of the tracking period (Dec 1 - Nov 30)
- Generate invoices at $20 per unfulfilled hour, to be billed with membership renewal
- Automatic integration with the membership renewal billing process

**Admin Reporting Tools**
- Summary report for Directors showing compliance statistics, including hours logged by category and by member
- Exportable CSV or PDF reports for end-of-year billing and record-keeping

**Data Analytics & Insights**
- Track patterns in volunteer participation by date and event type
- Identify high- and low-engagement events to assist Directors in planning future activities

**Mobile-Friendly Interface**
- Responsive design to allow members to easily log hours and view their profile from mobile devices
- Streamlined, user-friendly interface for quick access to event schedules and individual hour logs

#### Some mockup pages include:

  * Home Page
  * Member Dashboard
  * Volunteer Activity Log
  * Activity Approval Page (Director Access)
  * Upcoming Events Page
  * Event Tracking and Check-in Page
  * Annual Summary and Billing Page
  * Settings and Profile Management
  * Policy Overview Page
  * Admin Dashboard

  
### Use case ideas

Whether or not the following bullet points list all pages or not, the completed use case should show an end-to-end scenario of using the system.

**Log Volunteer Hours:**
Members log hours for events; directors review and approve.

**Event Check-In:**
Members check in at events for auto-logging of attendance and hours.

**Event Sign-Up:**
Members sign up for upcoming volunteer opportunities.

**Billing for Unfulfilled Hours:**
At year-end, members lacking required hours are billed for the deficit.

**Hour Approval Workflow:**
Directors approve or reject logged hours.

**Member Dashboard:**
Members view their progress on required hours and event history.

**Annual Report:**
Directors generate reports on volunteer participation by member and event.

**Policy Access and FAQ:**
Members read policy details and FAQs on the Work, Play, Pay Policy.

**Task Assignment for Events:**
Organizers assign specific tasks to event participants.

**Hour Deficit Reminders:**
Members receive notifications if they are on track to fall short of hours. 


### Beyond the basics

After implementing the basic functionality, here are ideas for more advanced features:

  * Notifications via email and/or SMS.
  * Barcode scan check-in for activity