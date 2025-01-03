# backend_interview_questions

# JavaScript, Node.js, and MongoDB Concepts

This repository contains a comprehensive collection of JavaScript, Node.js, and MongoDB concepts, including explanations, code snippets, and examples. It serves as a reference guide for developers looking to enhance their understanding of these technologies.

## Table of Contents

1. [JavaScript Concepts](#javascript-concepts)
   - [What is JavaScript?](#what-is-javascript)
   - [Variable Declarations: var, let, and const](#variable-declarations-var-let-and-const)
   - [Comparison Operators: == vs ===](#comparison-operators--vs-)
   - [Async/Await](#asyncawait)
   - [Array Methods: map, filter, reduce](#array-methods-map-filter-reduce)
   - [Shallow Copy vs Deep Copy](#shallow-copy-vs-deep-copy)
   - [Promises: Promise.all and Promise.any](#promises-promiseall-and-promiseany)
   - [Local Storage vs Session Storage](#local-storage-vs-session-storage)
   - [Synchronous vs Asynchronous Functions](#synchronous-vs-asynchronous-functions)
   - [SQL vs NoSQL](#sql-vs-nosql)
   - [Higher-Order Functions](#higher-order-functions)

2. [Node.js Concepts](#nodejs-concepts)
   - [What is Node.js?](#what-is-nodejs)
   - [NPM (Node Package Manager)](#npm-node-package-manager)
   - [Error Handling in Node.js](#error-handling-in-nodejs)
   - [Express.js](#expressjs)
   - [Authentication vs Authorization](#authentication-vs-authorization)
   - [Streams and Buffers](#streams-and-buffers)
   - [Cluster and Child Processes](#cluster-and-child-processes)

3. [MongoDB Concepts](#mongodb-concepts)
   - [What is MongoDB?](#what-is-mongodb)
   - [Concept of a Collection](#concept-of-a-collection)
   - [Primary Key](#primary-key)
   - [Foreign Key](#foreign-key)
   - [Replication in MongoDB](#replication-in-mongodb)

4. [Miscellaneous](#miscellaneous)
   - [Docker](#docker)
   - [Load Balancing](#load-balancing)

## JavaScript Concepts

### What is JavaScript?
JavaScript is a high-level, interpreted programming language that is widely used for creating dynamic and interactive web pages.

### Variable Declarations: var, let, and const
- `var`: Function-scoped/global scoped, can be re-declared and re-assigned.
- `let`: Block-scoped, can be re-assigned but not re-declared.
- `const`: Block-scoped, cannot be re-assigned or re-declared.

### Comparison Operators: == vs ===
- `==`: Compares two variables, ignoring the datatype.
- `===`: Compares two variables, checking both value and datatype.

### Async/Await
Async/await is a modern way to work with asynchronous code, making it more readable and sequential.

### Array Methods: map, filter, reduce
- `map()`: Transforms every element of an array and creates a new array.
- `filter()`: Removes unwanted elements and creates a new array.
- `reduce()`: Reduces all array elements into a single value.

### Shallow Copy vs Deep Copy
- **Shallow Copy**: Duplicates only the outer object; inner objects are shared.
- **Deep Copy**: Creates a full, independent copy of the object.

### Promises: Promise.all and Promise.any
- `Promise.all`: Resolves when all promises are resolved; rejects if any promise fails.
- `Promise.any`: Resolves when any one of the promises resolves; rejects if all promises fail.

### Local Storage vs Session Storage
- **Local Storage**: Data persists even after the browser is closed.
- **Session Storage**: Data is cleared when the browser or tab is closed.

### Synchronous vs Asynchronous Functions
- **Synchronous**: Blocking architecture; each operation must complete before the next starts.
- **Asynchronous**: Non-blocking architecture; tasks can run simultaneously.

### SQL vs NoSQL
- **SQL**: Structured Query Language, suitable for complex queries and transactions.
- **NoSQL**: Flexible data models, not strictly adhering to relational models.

### Higher-Order Functions
A higher-order function is a function that takes one or more functions as arguments or returns a function.

## Node.js Concepts

### What is Node.js?
Node.js is a runtime environment that executes JavaScript code outside the browser, commonly used for building scalable server-side applications.

### NPM (Node Package Manager )
NPM is the default package manager for Node.js, used to install, share, and manage dependencies for Node.js projects.

### Error Handling in Node.js
Errors in Node.js can be handled using try-catch blocks for synchronous code and using callback functions, Promises, or async/await for asynchronous code.

### Express.js
Express.js is a popular framework for building web applications and APIs with Node.js, providing a robust set of features for web and mobile applications.

### Authentication vs Authorization
- **Authentication**: The process of verifying the user’s identity.
- **Authorization**: The process of determining what actions a user is allowed to perform.

### Streams and Buffers
- **Streams**: A type of data-handling method used to read or write input/output sequentially.
- **Buffers**: Temporary storage for raw binary data, allowing efficient handling of data streams.

### Cluster and Child Processes
- **Cluster**: Allows you to create multiple copies of your app running on different CPU cores to improve performance.
- **Child Processes**: Separate instances of your app or another program that run alongside the main app, enabling parallel task execution.

## MongoDB Concepts

### What is MongoDB?
MongoDB is a NoSQL database management system that uses a document-oriented data model, storing data in flexible, JSON-like BSON documents.

### Concept of a Collection
A collection in MongoDB is a group of documents that share a similar structure, equivalent to a table in a relational database.

### Primary Key
A primary key is a unique identifier for a record in a database table.

### Foreign Key
A foreign key is a field in a database table that creates a link between two tables.

### Replication in MongoDB
Replication is the process of creating and maintaining multiple copies of data across different servers to ensure data availability and reliability.

## Miscellaneous

### Docker
Docker is a platform for developing, shipping, and running applications in containers, providing a consistent environment for development and deployment.

### Load Balancing
Load balancing distributes incoming network traffic across multiple servers to ensure no single server is overwhelmed, improving application availability and responsiveness.