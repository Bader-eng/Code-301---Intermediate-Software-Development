# What Is Node.js?
* Node.js is an event-based, non-blocking, asynchronous I/O runtime
that uses Google’s V8 JavaScript engine and libuv library.

## Node.js Has Excellent Support for Modern JavaScript:
* As can be seen on this compatibility table, Node has excellent support for ECMAScript 2015 (ES6) and beyond. 
As you’re only targeting one runtime (a specific version of the V8 engine), this means that you can write your 
JavaScript using the latest and most modern syntax. It also means that you don’t generally have to worry about 
compatibility issues — as you would if you were writing JavaScript that would run in different browsers.

## What Is Node.js Used For?
* These build tools come in all shapes and sizes, and you won’t get far in a modern JavaScript landscape without bumping into them. 
They can be used for anything from bundling your JavaScript files and dependencies into static assets, to running tests, or automatic 
code linting and style checking.

## The Node.js Execution Model:
*Node.js, however, is single-threaded. It’s also event-driven, which means that everything that happens in Node is in reaction to an event.
For example, when a new request comes in (one kind of event) the server will start processing it. If it then encounters a blocking I/O operation, 
instead of waiting for this to complete, it will register a callback before continuing to process the next event. When the I/O operation has finished
(another kind of event), the server will execute the callback and continue working on the original request. Under the hood, Node uses the libuv library 
to implement this asynchronous (that is, non-blocking) behavior.
