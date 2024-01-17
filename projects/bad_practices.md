---
layout: project
type: project
image: img/difficulty/smell.jpeg
title: "Bad Practices for Novices to Avoid"
permalink: projects/BPS
# All dates must be YYYY-MM-DD format!
date: 2018-07-01
labels:
  - Advice
summary: A compendium of bad practice smells in software engineering education
---

# Bad Practices for Novices to Avoid

Here is a compendium of bad practices I've observed are common beginning programmers. If you recognize yourself doing any of these, try to the advice given in Better Practice. There more a bad practice becomes a habit, the more difficult it will be to change to a practice that is more effective! 

**Bad Practice:** Blindly copying code into your code from another source (such as Stack Overflow, chartGBT, or a classmate). 

**Why this is bad:** The context for your situation will likely be different so the code you copy is unlikely to be exactly what you need. This may be simple things such as the variables are not named the same as your variables or can me more complicated such as the code doesn't address exactly what you want (because the source of your code doesn't know exactly what you want within the context of your situation). Also, the code you copy may have problems or does things in a way that doesn't suit your situation (such as the use of more advanced techniques you don't understand or are "overkill"), or use components/libraries/functions you don't have access to or are unnecessary. You will likely try to add too much code at once and will have trouble integrating it into your code. You will not be sure where to put it in your code. This will likely mess up your structure, increase the complexity, and make it much harder to find and fix problems.  Even if you do get code that "works" you will find it harder to extend this code to complete your program or do other things later (we often build on previous work).

**Better Practice:** If you're stuck on what code to write start by "going backward" to ensure that you clearly understand what you want to do and how it will do it. If you find you are confused about how to do something, go backward again and simplify the situation until it's very clear what you want to do. Then move forward by thinking about how you can do what's wanted. When this is clear, then you think about what code you need to write to accomplish this by breaking it down into simple steps (this is the algorithmic thinking part!) and translating this into code. Usually, this will be pretty straightforward. If you find you don't know how to write the code you want, then do some research. Look for examples of code that are similar to what you want to do. When you find such examples, do not blindly copy them into your code! Study the example and if you understand it well, think about if it can be easily adapted to what you want. If it can, copy a small part of the code into your code and start adapting it being sure to test it carefully before you copy more code. If you find that adapting it may be too much trouble, then use the code to "inspire" you on how to do what you want and start writing your own code rather than copying the example. You will find that this will often take less time and you will have less trouble with the code you write!

---

**Bad Practice:** Trying random code you don't understand hoping you will "see" what to do from it.

**Why this is bad:** Every line of code will have a specific purpose for being there. The purpose is dictated by the design choices you make on how to accomplish what is wanted. Random code does not "flow" from the design so it will unlikely by chance do what you want.

**Better Practice:** Do not ever write (or copy) code that you do not clearly know flows from your design. You should know exactly what each line of code does (or is supposed to do) and why it's there. If you do not, DELETE this code! If you are unclear on the design, "go backward" to clarify that you know exactly what is wanted (or at least what you want).

---
**Bad Practice:** Writing code without sufficient analysis and design

**Why this is bad:** Students often feel that unless they're writing code, they're not making progress.

**Better Practice:** Always follow the "What - how - do - test" cycle. 

---

**Bad Practice:** Continuing to write (or copy) code when you are stuck or having problems hoping that things will "fall into place" or the problem will go away with more code.

**Why this is bad:** The more code you write, the more problems you add and the harder it will be to find and fix. Eventually, your code becomes so muddled that you cannot work with it anymore.

**Better Practice:** Slow down! Always leave your code in a "working" state. Frequently test your code. A good rule of thumb is to write no more than 7 lines of code before you test (of course this may vary depending on what you are writing as some situations will require more code to be in a place you can conduct a test). If you get stuck, try simplifying what you are doing. This may mean taking a smaller step toward implementing something. When you get that working, then take another small step. If you are still stuck and unable to progress, revert your code to the last place that was working (you may need to comment out code you have been trying). When things are working again, try working on something different and come back to your problem area later. The additional structure you add may help you see a way to address your problem or taking a break and coming to it fresher may offer a solution. If find yourself having many problems and are totally lost, consider starting over! Delete (or archive) what you have been working on and start again. You are unlikely to run into the same problems again and you will find that it takes less effort and get better results to start anew rather than try to find, fix, and patch together your previous code.

---
**Bad Practice:** Not following coding standards or formatting guidelines.

**Why this is bad:** You may not be aware of the importance of following coding standards and guidelines, which can lead to poorly structured code that is difficult to read and maintain. It also makes it difficult for you to share your code with others or for others to provide help when you are having trouble with your code.

**Better Practice:** xxx

---
**Bad Practice:** Overthinking the problem and overcomplicating solutions

**Why this is bad:**  Inexperienced programmers tend to think problems are more complicated than they actually are leading to overcomplicated solutions and dismissing simple and straightforward approaches as "too easy to be correct". This can lead to getting stuck in "analysis paralyses" or hacking your way to a solution with more complex and difficult-to-maintain code.

**Better Practice:** xxx

---
**Bad Practice:** Writing too much code before testing

**Why this is bad:** Students may not see the importance of testing and debugging their code, or they are in a hurry to get something done which can lead to bugs and errors in their applications that are difficult to fix and fix.

**Better Practice:** xxx

---
**Bad Practice:** Poor documentation, not commenting code

**Why this is bad:** : It's impossible to keep too many details about what you are doing and how you will do it in your head while you are writing code, Documentation helps you understand what's wanted and think through more clearly how to do. It helps organizing and guiding development and is crucial for maintaining and updating your code, particularly if it's shared with others.  Students may overlook this aspect of development or not understand how to properly document their code.

**Better Practice:** Write your comments first in an outline format then write the code to follow this outline. Aim to have at least 90 lines of comments for every 100 lines of code. Try not to have more than 7 lines of code without any comments. 

---
**Bad Practice:** Not seeking feedback or assistance when having trouble

**Why this is bad:**  Students may be hesitant to seek feedback or assistance from the instructor or their peers because they fear looking stupid or that everyone understands better than they do. They may feel that they must persevere or quietly give up. This can lead to increased frustration and slower progress and missed opportunities for learning and improvement.

**Better Practice:** xxx

---
**Bad Practice:** Not understanding the requirements

**Why this is bad:** Students may be overly focused on writing code and not fully understand or misunderstand the requirements of the project they are working on. This inevitably leads to solutions that don't fully meet the needs of the user.

**Better Practice:** xxx

---
**Bad Practice:** Not using version control

**Why this is bad:** Version control is a crucial tool that students may not understand its importance or how to use it effectively. Programming is often exploratory and experimental. You often go down a path that is un-viable or you break the code in such a way that it becomes a quagmire to fix. Sometimes previous solutions that you explore and discard can be useful later or revisited. Code is accidentally modified or deleted

**Better Practice:** xxx

---
**Bad Practice:** Poor naming of variables, functions, files, classes

**Why this is bad:** The reason these considerations are important is that the names you choose can have a significant impact on the readability, maintainability, reusability of your code. Choosing clear, meaningful, and consistent names will help other developers understand your code and make it easier to maintain and update over time.


**Better Practice:** Keep the following considerations in mind when choosing a name:
  - Clarity: The name should clearly describe what the variable, function, file, or class does. It should be easy to understand and not confuse other developers who may be reading or using your code.
  - Consistency: The naming convention should be consistent throughout the codebase. This will help make the code easier to read and maintain.
  - Length: The name should be long enough to be descriptive but not too long that it becomes cumbersome to type or read. Avoid using reserved keywords: Avoid using reserved keywords as variable names, function names, or class names.
  - Meaningfulness: Use meaningful names instead of using short, abbreviated, or cryptic names that can be difficult to understand.
  - Avoid special characters: Avoid using special characters like underscores, hyphens, or spaces in the name. Instead, use camelCase or snake_case for variable and function names.
  - Follow naming conventions: Different programming languages have different naming conventions. Following the conventions of the language will help make the code more readable and maintainable.

