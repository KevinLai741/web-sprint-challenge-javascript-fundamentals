# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

Each of these have their own differences and function. With map, it returns a brand new array, which does not manipulate the original array, and it'll need a return statement. With reduce, it does not return a new array, it returns a single value and is usually used for multiplication/addition. With filter, it will filter data based on something that can be equated to either true or false, it'll return a new array and does not manipulate the original. A use case for map is to map an array of numbers to an array of square roots. A use case for reduce is to sum or multiply all the values of an array. A use case for filter is when we want to filter out an array with certain values.

2. Explain the difference between a callback and a higher order function.

The difference between a callback and a higher order function is that a callback function is a function that is passed into another function as an argument; while, a higher order function is a function that receives other functions.

3. Explain what a closure is.

A closure is when an inner function reaches out of its scope to grab a variable defined in an outer function. Closures are useful because they let us associate the data with a function that operates on that data.

4. Describe the four principles of the 'this' keyword.

The four principles of the 'this' keyword is window binding, implicit binding, explicit binding, and new binding. Window binding is when if we do not give 'this' any context, it will return the window, the global object in node or undefined in strict mode. Implicit binding applies to objects with methods, when the function is invoked, to the left of the dot is what 'this' refers to. Explicit binding is when we tell a function what the 'this' keyword should be using when we use .call, .apply or .bind. New binding is when the function is invoked with a new keyword that the 'this' keyword inside the function is bound to the new object being constructed.

5. Why do we need super() in an extended class?

We need super() in an extended class, because with extend it is used to create a child class of another class (parent) and with super(), it gets access to the parent's constructor method and properties.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://notion.so.bloomtech.BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade
