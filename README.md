# [Reversed Strings](https://www.codewars.com/kata/reversed-strings)

This kata asks you to write a function that reverses a string.
* It takes a string as an argument.
* It returns that string in reverse.

They give the following example:

`solution('world'); // returns 'dlrow'`

This was my final solution:

```js
function solution(str){
  return str.split("").reverse().join("");
}
```


### Index
* [Input Classifications](#input-classifications)
* [Solution Explanation](#solution-explanation)
* [Constraints](#constraints)
* [Resource Estimation](#resource-estimation)
* [Scaffolding](#scaffolding)
* [Bugs & Challenges](#bugs-challenges)
* [Language Features](#language-features)
* [Use Cases](#use-cases)
* [Learning Journal](#learning-journal)

---

## Input Classifications

**What characteristics of your inputs are important for your solution?**
It is important that the input will be a single block of characters. This means that it will have to be split into individual characters, their order will have to be reversed, and they will have to be re-integrated into a single string.  

**How did you use this information to select your test cases?**
I still have to make my own test cases.


[TOP](#index)

___

## Solution Explanation

I used the `.split` method with an empty string as its parameter, `.split("")`, to separate the input into individual characters.

Once I had an array of individual characters, I used the `.reverse` method to reverse their order.

The next issue to be solved was to re-combine the individual characters into one string. To do this, I used the `.join` method, again with an empty string as parameter: `.join("")`. This re-combined the split and reversed characters into a single string.

[TOP](#index)

---

## Constraints

I didn't place any constraints as such, but I did try to write the code as compactly as possible.

[TOP](#index)

___


## Resource Estimation

I'm not sure about the use of resources required.


[TOP](#index)

___

## Scaffolding

Provide a link to Gist you used to construct your solution's scaffolding.  What difficulties did you have making it?  How helpful was it in coming up with your finished solution?

[TOP](#index)

___

## Challenges & Bugs

What particular challenges & bugs did you come across when you were filling in your scaffolding?

Were they logic bugs? Language bugs?

Did you have trouble keeping track of which part of the challenge you were solving?

[TOP](#index)

___

## Language Features

List the language features used in your solution.

The focus of these exercises are to strengthen you problem solving skills, not to learn the newest ES6 tricks. When you have the choice between to different language features it is better to choose the option that is easiest to read, most common, or most consistent with the rest of your solution.  

Keeping track of the language features you use will enable you separate the problem solving strategy from the implementation.  Being aware of this difference will be an asset later on when you're faced with larger applications and popular frameworks.

[TOP](#index)

---
## Use Cases

List 5+ use cases for your solution.  They can be stand-alone, part of an application, or impractical.  Your use cases can be overly complicated, or very basic. What's important is that you come up with as many and as diverse use cases as possible.


[TOP](#index)

---

## Learning Journal

Things I learned studying this problem:


New vocabulary:


Things I struggled with:


Lessons to apply for next time:



[TOP](#index)

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>
