# CODE FELLOWS - CODE 301

## DAY 01 CLASS 00

### [HOME](../README.md)

## CORE SYLLABUS

## Course Information

- Course Level: Code 301

## Course Prerequisites

- Code 102
- Code 201

## Course Description

In this intensive course, you will study the common core of software development, including the MVC pattern, object-oriented and functional programming, and computer science fundamentals such as basic data structures and algorithms. Come learn how to create and deploy web apps in the “MERN” stack with Mongo, Express, React, and Node.js, with the help of third-party APIs and libraries from around the web.

## Program Learning Outcomes

Students will learn to write clean, well-tested, JavaScript and React code, integrate with remote APIs, and interface with MongoDB using industry best practices.

## Student Learning Outcomes

Upon satisfactory completion of this course, a student should be able to:

### Describe and Define

#### Concepts

- Web Request-Response Cycle
- Stateful DOM Management with React Components
- Express.JS
- JSON and 3rd-party APIs
- Persistence with MongoDB
- Styling Libraries
- Server-Side Routing
- Services and RESTful APIs
- Functional Programming
- AJAX and Asynchronous Programming
- MVC Architecture
- Authentication
- Deployment with cloud services like Heroku

#### Daily Practice in Data Structures

- Strings
- Arrays
- Objects
- Functional Programming

#### Languages

- CSS Frameworks
- Intermediate JavaScript
- React

#### Environments and Tools

- Unix and the Command Prompt
- Git and Github
- A Text Editor
- Chrome Dev Tools
- HTTP with Postman
- MongoDB and Mongoose
- Auth0
- Trello Project Management

### Execute

- Collaboratively design and create web applications from scratch using MVC patterns, built with professional-grade HTML, CSS, and JavaScript using the React JavaScript library
- Work with string, array, and object data structures and algorithms to solve code challenges with pure JavaScript programming
- Build dynamic front-end and back-end applications deployed to cloud platforms
- Explain the fundamentals of how the World Wide Web works, over the internet
- Utilize dependency management techniques to build with third-party libraries such as ExpressJS and React-Bootstrap
- Persist data in a NoSQL database, sourced from third-party APIs or user-generated content
- Authenticate users using a third-party OAuth library.
- Follow agile software development practices during week-long sprints, including:
  - pair-programming
  - stand-ups
  - daily retrospectives
  - project management with Kanban boards
  - regular refactoring
  - and working in a shared codebase

## Course Schedule

### Module 1

| Class # | Topic | Lab |
|-----------------|-----------|----------|
| 01 | React and Component-Based Architecture | Initialize React Application |
| 02 | React State and Props | Create gallery of images from common state |
| 03 | Functions as Props | Manipulate state from child component via passed function |
| 04 | React and Forms | Filtering state based on form inputs, events |
| 05 | Conditional Rendering, Routing | Portfolio - 3rd party application modifications |

### Module 2

| Class # | Topic | Lab |
|-----------------|-----------|----------|
| 06 | Asynchronous Code and Third Party APIs | Retrieve remote data from React |
| 07 | Express Servers | Express API server with mock data |
| 08 | APIs | Retrieve and repurpose remote API data |
| 09 | Modularization, Refactoring | Modularize Express API server |
| 10 | Persistence | Implement in-memory cache for non-volatile API data |

### Module 3

| Class # | Topic | Lab |
|-----------------|-----------|----------|
| 11 | Mongo, Mongoose and Data Modeling | Implement READ (CRUD) with Mongo and Express |
| 12 | Creating and Deleting resources | Implement Create and Delete (CRUD) in Full Stack App |
| 13 | Updating Resources | Implement Update (CRUD) in Full Stack App |
| 14 | Diversity, Equity, Inclusion in Tech | Final Exam |
| 15 | Authentication | Add OAuth to Full Stack App with React |

### Module 4 - Final Project

| Class # | Deliverables |
|-----------------|-----------|
| 16 | Wireframes, User Stories, Architecture Plan, DevOps, Documentation, Agreements|
| 17 | Phase 1 |
| 18 | MVP |
| 19 | Final Polish, Presentation Practice |
| 20 | Live Project Presentations |

## DATA STRUCTURES AND ALGORITHMS SYLLABUS
### Course Description
Data Structures and Algorithms 301 is designed to introduce students the concepts of TDD and algorithmic thinking using high level data structures (Objects and Arrays) in JavaScript

### Course Materials
* Code Editor/IDE

### Program Learning Outcomes
Develops algorithmic thinking and problem solving skills, working under stress, and visual breakdowns.

## Student Learning Outcomes
Upon satisfactory completion of this course, a student should be able to:

### Describe and Define
* Best use cases for the common data structures
* Suitability to task (best option) for JavasScript internal methods
* Rules, methods, limitations, use cases for the major data structures
  * Arrays
  * Objects

### Execute & Demonstrate
* Array Methods: ```.forEach()```, ```.map()```, ```.filter()```, ```.reduce()```
* Array Sorting
* Array manipulation: Loops, splice, slice
* String manipulation: splice, slice, substrings
* Regular Expressions
* Algorithmic Thinking
* Test Driven Development

## Course Schedule
|Class #	|Topic|
|---|-------------------------------|
|01 |Array.forEach()                |
|02 |Array.map()                    |
|03 |Array.filter()                 |
|04 |Array.sort()                   |
|05 |Array.reduce()                 |
|06 |Value vs Reference             |
|07 |Other Array and String methods |
|08 |Regular Expressions            |
|09 |Object Iteration               |
|10 |2 Dimensional Arrays           |
|11 |Chaining Methods               |
|12 |Regular Expressions            |
|13 |String Manipulation            |

## ADDITIONAL RESOURCES

## READING NOTES

### Constructor Functions & Prototypes
```js
const Animal = function(name, legs) {
  this.name = name;
  this.legs = legs;
  this.eat = function() {
    this.isEating = true;
  }
}

Animal.prototype.walk = function() {
  this.isWalking = true;
}

const Dog = function(name, legs) {
  Animal.call(this, name, legs);
}

Dog.prototype = Object.create(Animal.prototype);

let puppy = new Dog('blake', 4);
puppy.walk();
puppy.eat();
console.log(puppy);
console.log(puppy instanceof Animal);
console.log(puppy instanceof Dog);
```
### ES6 Classes
```js
class Animal {

  constructor(name, legs) {
    this.name = name;
    this.legs = legs;
  }

  walk() {
    this.isWalking = true;
  }

  eat() {
    this.isEating = true;
  }
}

class Dog extends Animal {

  constructor(name, legs, furType) {
    super(name,legs);
    this.furType = furType;
  }

  speak() {
    console.log('Wooof!');
  }
}

let rosie = new Dog('rosie', 4, 'Short Hair');
rosie.walk();
rosie.eat();
console.log(rosie);
rosie.speak();
```


## CLASS NOTES

## LINKS

### [301 GitHub](https://github.com/codefellows/seattle-code-301d85)
### [Prep: Arrow-functions](https://github.com/jonarmstrong-github/arrow-functions/blob/main/app.js)
### [Prep: ES6 Classes Assignment](https://codefellows.github.io/code-301-guide/curriculum/prework/classes/LAB.html)
### [Prep: ES6 Classes Work](https://replit.com/@JonArmstrong/ES6-Classes#index.js)

## VOCABULARY

## THINGS I WANT TO KNOW MORE ABOUT

### [HOME](../README.md)