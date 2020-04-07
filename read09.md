## Concepts of Functional Programming in Javascript
What is functional programming?
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

Pure functions
The first fundamental concept we learn when we want to understand functional programming is pure functions. But what does that really mean? What makes a function pure?
So how do we know if a function is pure or not? Here is a very strict definition of purity:
It returns the same result if given the same arguments (it is also referred as deterministic)
It does not cause any observable side effects

## ure functions benefits
The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:
Given a parameter A → expect the function to return value B
Given a parameter C → expect the function to return value D
A simple example would be a function to receive a collection of numbers and expect it to increment each element of this collection.


The idea of functions as first-class entities is that functions are also treated as values and used as data.
Functions as first-class entities can:
refer to it from constants and variables
pass it as a parameter to other functions
return it as result from other functions
The idea is to treat functions as values and pass functions like data. This way we can combine different functions to create new functions with new behavior.


