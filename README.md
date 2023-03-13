# JavaScript Functions Homework

You will be writing some functions in JavaScript. JavaScript was designed to work in the browser.  But we can use `node` to run JS in our terminal!

## Objectives 

- learn to write functions
## Repo Instructions

- **Fork** this repo to your account by clicking on the **fork** Button at the top of this page. 

![](https://upload.wikimedia.org/wikipedia/commons/3/38/GitHub_Fork_Button.png)

*A **fork** is a copy of this repository. This forked repository will appear on your github account.*

- Find the repository on *YOUR* account (ie yourUserName/js-hw-loops) and click on the green `Code` button at the top of the page.

![](./images/githubCodeButton.png)

- Copy the path in the dialogue box
- Navigate to a location on **your local computer in VSCode** where you keep your homework 
- Clone this repository by typing the following command in your terminal

```
clone [`path that you just copied`]
```

For example: 

```bash 
clone git@github.com:{your-github-user}/js-hw-functions.git
```
## Task Instructions
- Navigate into the folder titled `js-hw-functions`
- Create a new `js` file for each problem. Then, run a file javascript file using `node` from your terminal like this:

```bash
$ node theNameOfTheFile.js
```

## Celsius to Fahrenheit conversion
Write a function that takes a temperature in Celsius, converts it Fahrenheit, and returns the value.

`Formula:  F = (C * 9/5) + 32`


## Fahrenheit to Celsius conversion
Write a function that takes a temperature in Fahrenheit, converts it to Celsius, and returns the value.

`Formula:  C = (F - 32) * 5/9`

## is_even function
Write a function that accepts a number as an argument and returns a Boolean value. Return `True` if the number is even; return `False`if it is not even.

## is_odd function
Write an `is_odd` function that uses the return value from your `is_even` function to determine if a number is odd and return `It's ODD!` (hint: remember conditions?).

## only_evens function
Write a function that accepts an Array of numbers as an argument.
Return a new Array that includes only the even numbers.

*example output*
```
only_evens([11, 20, 42, 97, 23, 10])
# Returns [20, 42, 10]
```
(hint: you can call a function that checks if a number `is_even`!)

# Medium

## Find the smallest number

Write a function `smallest` that accepts an Array of numbers as an argument.  It should return the smallest number in the Array.


