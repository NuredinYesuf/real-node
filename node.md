# Node.js

Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine. It allows you to run JavaScript on the server side.

## Features

- **Asynchronous and Event-Driven**: All APIs of Node.js library are asynchronous, that is, non-blocking.
- **Very Fast**: Being built on Google Chrome's V8 JavaScript Engine, Node.js library is very fast in code execution.
- **Single Threaded but Highly Scalable**: Node.js uses a single-threaded model with event looping.

## Installation

To install Node.js, you can download the installer from the [official Node.js website](https://nodejs.org/).

## Example

Here is a simple example of a Node.js application:

```javascript
const http = require('http');

const hostname = '127.0.0.1';
const port = 3000;

const server = http.createServer((req, res) => {
    res.statusCode = 200;
    res.setHeader('Content-Type', 'text/plain');
    res.end('Hello World\n');
});

server.listen(port, hostname, () => {
    console.log(`Server running at http://${hostname}:${port}/`);
});
```

## Resources

- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Node.js GitHub Repository](https://github.com/nodejs/node)

