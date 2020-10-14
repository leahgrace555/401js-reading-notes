# Read: Class 02

## Questions:

1. Why would you want to run JavaScript code outside of the browser?
- The browser is only one type of runtime environment for JavaScript code. Javascript written for and run int he browser is front-end javascript, while Javascript written and run outside of the borwser (such as in a Node environment) is back-end Javascript and allows us to do things such as hit APIs and serve files

2. What is the difference betweena module and package?
- A module is a single file with some sort of functionality, while a package is a directory, or collection, of modulesin a directory.

3. What does node package manager do?
- NPM is repository for open-source node projects that has a utility which aids in the installation, version and dependency management for different node packages one might want to use for a project.

4. Provide snippets of code showing 3 different ways to export a node module
````
exports.examplemodule = exampleModule; //goes at the end of a file

const example = require('./fileWithExample'); //goes at the beginning of a file you want to use the export in

exports.example = () => {
  return 'exampleThing';
}; //can be used as you go, not just at the end of a file
````

## Vocabulary: 

**Ecosystem:** The collection of software projects developed in the same environment, whether it be social, cooperate, technical etc... 

**Node.js**: A runtime environment for back-end javascript

**Module:** an individual js file

**Package** a directory or collection of modules

**Npm (node package manager):** a utility for managing, installing and contributing to packages for Js projects

**Server:** A piece of computer hardware or software that provides functionality to other devices, or "clients".

**Environment:** Refers to the hardware and software in which the code is being written and run

**Interpreter:** A program that can run executable code without having previously compiled 

**Compiler:** Software that translates code written in a higher language to instruction that can be understood by the computer 
