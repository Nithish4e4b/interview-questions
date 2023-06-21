
### 1) What is Node.js?

Node.js is Server-side scripting which is used to build scalable programs. It is a web application framework built on Google Chrome's JavaScript Engine. It runs within the Node.js runtime on Mac OS, Windows, and Linux with no changes. This runtime facilitates you to execute a JavaScript code on any machine outside a browser.


### 2) What is the purpose of Node.js?

These are the following purposes of Node.js:

- Real-time web applications
- Network applications
- Distributed systems
- General purpose applications

### 3) What are the advantages of Node.js?

- Node.js is very fast because it builds on Google Chrome's V8 JavaScript engine. Its library is very fast in code execution.
- Node.js is single threaded but highly scalable.
- Node.js provides a facility of no buffering. Its application never buffers any data. It outputs the data in chunks.
- Node.js is asynchronous and event-driven. All API?s of Node.js library are non-blocking, and its server doesn't wait for an API to return data. It moves to the next API after calling it, and a notification mechanism of Events of Node.js responds to the server from the previous API call.

### 4) What is call back hell?
_Callback Hell is essentially nested callbacks stacked below one another forming a pyramid structure_.


###  What is an asynchronous API?

All the API's of Node.js library are asynchronous means non-blocking. A Node.js based server never waits for an API to return data. The Node.js server moves to the next API after calling it, and a notification mechanism of Events of Node.js responds to the server for the previous API call.

### How can you avoid callbacks?

To avoid callbacks, you can use any one of the following options:

- You can use **modularization**. It breaks callbacks into independent functions.
- You can use **promises**.
- You can use **yield** with Generators and Promises.

### What types of tasks can be done asynchronously using the event loop?

- I/O operations
- Heavy computation
- Anything requiring blocking

### What is npm? What is the main functionality of npm?

npm stands for Node Package Manager. Following are the two main functionalities of npm:

- Online repositories for node.js packages/modules which are searchable on search.nodejs.org
- Command line utility to install packages, do version management and dependency management of Node.js packages.