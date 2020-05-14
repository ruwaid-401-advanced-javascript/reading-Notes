# read 1

## Why would you want to run JavaScript code outside of a browser?
the comfort of programming everything, the frontend and the backend, in a single language.

## What is the difference between a module and a package?
modules are not required to have a package.json file, not all modules are packages. Only modules that have a package.json file are also packages
A package must contain a package.json file in order to be published to the npm registry.

## What does the node package manager do?
installs, updates or uninstalls Node.js packages in the application


## Provide code snippets showing 3 different ways to export a function from a node module
1. module.exports = functionName
2. module.exports = {
  functionOne: function1,
  functionTwo: functionTwo,
  functionThree: function() {
    console.log('Hello');
  }
3. module.export function hi(){
	conole.log('hi');
}
/*********************************************************************************************************************/
* ecosystem: "a collection of software projects, which are developed and co-evolve in the same environment”
* Node.js: is a JavaScript runtime built on Chrome's V8 JavaScript engine. As an asynchronous event-driven JavaScript runtime
* V8 Engine: V8 is Google’s open source high-performance JavaScript and WebAssembly engine, written in C++, and engine is a computer program that executes JavaScript (JS) code.
* package: A package is a file or directory that is described by a package.json file. 
* modules: A module is any file or directory in the node_modules directory that can be loaded by the Node.js require() function.
* npm: npm is the world's largest Software Library, A package manager is a collection of software tools that automates the process of installing, upgrading, configuring, and removing computer programs for a computer's operating system in a consistent manner
* server:  is a computer program or a device that provides functionality for other programs or devices, called "clients". This architecture is called the client–server model,
* environment: The environment is quite literally everything installed on your machine which can affect either the development and or testing of your application
* interpreter: is a computer program that directly executes instructions written in a programming or scripting language, without requiring them previously to have been compiled into a machine language program.
* compiler: is a computer program that translates computer code written in one programming language (the source language) into another language (the target language).compiler is primarily used for programs that translate source code from a high-level programming language to a lower level language
/************************************************************************************************************************/
links
* ecosystem: 
  1. https://en.wikipedia.org/wiki/Software_ecosystem
  2. https://stackoverflow.com/questions/30690820/what-is-the-meaning-of-ecosystem-in-software

* Node.js: https://nodejs.org/en/about/

* V8 engine: 
  1. https://en.wikipedia.org/wiki/V8_(JavaScript_engine)
  2. https://v8.dev/
  3. https://en.wikipedia.org/wiki/JavaScript_engine

* npm: https://en.wikipedia.org/wiki/Package_manager

* server: https://en.wikipedia.org/wiki/Server_(computing)

* environment: https://www.quora.com/What-is-the-programming-environment

* interpreter: https://en.wikipedia.org/wiki/Interpreter_(computing)

* compiler: https://en.wikipedia.org/wiki/Compiler



