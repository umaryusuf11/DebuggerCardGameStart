# Overview
DO NOT EDIT SOURCE CODE IN THIS LAB EXCEPT WHERE EXPLICITLY INSTRUCTED

You will be submitting line numbers as answers to quiz questions - if at any point you think you might have altered your lines, check with your demonstrator or tutor.

In this lab you are going to work on code you should be familiar with from the previous weeks labs.

Results for this week will be submitted on Moodle to Week 4 Lab 4.1 Results.

You will have two sets of exercises:
* Basic tests of your debugger knowledge to show you can execute basic functions 
* More challenging work to find the specific locations of lines of code causing JUnit tests to fail

## Setup
* Fork - []()
* Clone your copy using gitbash
* Open using existing files in your IDE

## Debugging Basics
For each of the following, debug by running the main method in BlackJack.java.
* Make sure you run in debug mode so your breakpoints are observed.
* If you can't see an option to run the main method you want to use, look in the "Debug Configurations..." option below that.

### Warnings
* Find the class which is not making use of an import other than ArrayList and enter it's name in for Q1.

### Stack Traces
* Set a breakpoint on line 70 of BlackJack.java
* Run BlackJack main - when prompted, give the username bob and the value 2 for number of players
* An error should occur and create a stack trace for you to inspect before the breakpoint
* There is a single mistake on a single line of code that you need to add a -1 to.
THIS ISSUE MUST BE FIXED BEFORE CONTINUING - GET HELP IF YOU CAN'T FIX IT


### Breakpoints and Variable Inspection
* Run BlackJack main - when prompted, give the username bob and the value 2 for number of players
* What name does the player have when the breakpoint on line 70 is hit?

### Stepping In
* Carrying on from the hitting the debug point on line 70...
* (If you already stopped the process run BlackJack main - when prompted, give the username bob and the value 2 for number of players)
* Step into the code twice
* What class do you end up in?

### Setting a watchpoint
* Set a watchpoint on the variable maxscore in BlackJack.java
* Run BlackJack main - when prompted, give the username bob and the value 2 for number of players
* What is the SECOND line of code to access maxscore? 

## Advanced Debugging with Unit Tests and Debugger
Now you have the basics of using a debugger, it's time to apply those skills to identifying some harder to find issues.

### Player Name
* Find the class and line of code responsible for the name of the player not being bob. 

Run the JUnit tests on your code.

### JUnit Test Failure getScoreAceLow 
* Which class/line of code contains the mistake that is causing the getScoreAceLow test to fail?

### Wildcard mistake
* There is a final line of code somewhere in the project sometimes causing an error 
* Hint: the bug has not shown itself yet but happens with certain console input 
* Use debugging to identify the error
* Find the class and line of code that is responsible for the mistake  

 

