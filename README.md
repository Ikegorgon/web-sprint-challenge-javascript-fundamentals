# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks. 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results. 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 
    .map can be used to create a new array without modifying the original array. .reduce can be used to combine all the elements of an array, such as adding a list on integers, to give back one total value. .filter can be used to narrow down an array, such as selecting only values within a specific range such as begining with a specific letter.

2. Explain the difference between a callback and a higher order function.
    A callback function is a functioned that is passed as a parameter into another function, whereas the higher order function is the function recieving the callback function as a parameter.

3. Explain what a closure is.
    A closure is created in a function and explains the scope of said function. For example, if you create a function within a function you can use the scope of the main function within the subsidairy function, but not the other way around.

4. Describe the four principles of the 'this' keyword.
    "this" is used to refer to the object that it is made in, and the principles of it are Default Binding, Implicit Binding, Explicit Binding, and Contructor Call Binding. Default Binding means that the binding is going to the default object, which is the global object. Implicit Binding is used to bind to a new object that is made from a function. Explicit Binding is used to override the binding and give it a new value, such as using .apply

5. Why do we need super() in an extended class?
    super() is used to replave the .create() method and helps to initialize the parent attributes into the child object.


You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo [x]
2. Go into canvas and connect your repo to codegrade [x]
3. Clone your forked version of the repo [x]
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today [x]
5. cd into your repo [x]
6. open the terminal in your vs code and type `npm install` [x]
7. next type `npm run test` in your terminal [x]
8. Complete your work making regular commits to main/master; your codegrade score will update each time you make a push.


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

Please submit your project via codegrade by following [these instructions](https://bloomtech.notion.site/bloomtech/BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) (see part 2, submitting an assignment with codegrade).
