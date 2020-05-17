# read 2

## Name 3 advantages to Test Driven Development
1. receive fast feedback
2. TDD reduces time spent on rework.
3. TDD tells you whether your last change (or refactoring) broke previously working code.

## In what case would you need to use beforeEach() or afterEach() in a test suite?
If we have some work need to do repeatedly for many tests

## What is one downside of Test Driven Development
Tests need to be maintained when requirements change

## What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?
class: defines all of the properties that characterize a certain set of objects
constructor: Any object can specify its own properties. also any object can be associated as the prototype for another object, allowing the second object to share the first object's properties.

## Name a use case for a static method
is to group functions (that aren't really object-oriented and don't work on objects) together into classes for convenience and to create "alternate" constructors that are associated with the class their intended to construct.

## Write an example of a Higher Order function and describe the use case it solves
'function double(number){
  return number *2;
}'
'let arr = [1, 2, 3, 4, 8, 5];'
'arr.map(double);'

map function is an example for a higher order function, its take a function as an argument which multiply the number by two

## Terms 
* functional programming: is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects. 
* pure function:  is a function which Given the same inputs, always returns the same output, and Has no side-effects
* higher order function is any function which takes a function as an argument, returns a function, or both.
* immutable state: Immutable data cannot change its structure or the data in it.
* Objects: are complex and each object may contain any combination of the primitive data-types as well as reference data-types.and objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs.
* Object-oriented programming (OOP): is a programming paradigm based on the concept of "objects", In OOP, computer programs are designed by making them out of objects that interact with one another.
* class: is an extensible program-code-template for creating objects
* prototype: is a property can be used to add methods to existing constructors.
* super: a keyword used to access and call functions on an object's parent. When used in a constructor, the super keyword appears alone and must be used before the this keyword is used. 
* inheritance: is the mechanism of basing an object or class upon another object
* constructor: In class-based object-oriented programming, a constructor is a special type of subroutine called to create an object.
* instance: In object-oriented programming (OOP), an instance is a concrete occurrence of any object, existing usually during the runtime of a computer program.
* context: Context is always the value of the this keyword which is a reference to the object that “owns” the currently executing code or the function where it’s looked at.
* this: A property of an execution context (global, function or eval) that, in non–strict mode, is always a reference to an object and in strict mode can be any value.
* Test Driven Development (TDD): is a software development process that relies on the repetition of a very short development cycle: requirements are turned into very specific test cases, so its an evolutionary approach to development which combines test-first development where you write a test before you write just enough production code to fulfill that test and refactoring.
* Jest: is a JavaScript Testing Framework
* Continuous Integration (CI): is a development practice where developers integrate code into a shared repository frequently, preferably several times a day
* unit test: is a level of software testing where individual units/ components of a software are tested.The purpose is to validate that each unit of the software performs as designed.



## links
* functional programming, pure function, higher-order function, immutable state :
  * https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0
* Objects
  * https://www.geeksforgeeks.org/objects-in-javascript/
* OOP
  * https://en.wikipedia.org/wiki/Object-oriented_programming
* class 
  * https://en.wikipedia.org/wiki/Class_(computer_programming)
* prototype
  * https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object_prototypes
* super
  * https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/super
* inheritance
  * https://en.wikipedia.org/wiki/Inheritance_(object-oriented_programming)
* constructor
  * https://en.wikipedia.org/wiki/Constructor_(object-oriented_programming)
  * https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/constructor
* instance
  * https://en.wikipedia.org/wiki/Instance_(computer_science)
* context
  * https://towardsdatascience.com/javascript-context-this-keyword-9a78a19d5786
* Test Driven Development (TDD)
  * https://en.wikipedia.org/wiki/Test-driven_development 
* Jest
  * https://jestjs.io/
* unit test
  * http://softwaretestingfundamentals.com/unit-testing/




