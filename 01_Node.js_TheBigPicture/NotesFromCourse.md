# Whats make up NodeJS?

- V8 javastrip engine
- libuv - Asynchronous I/O, event loop 

# History of Node.js  
- 2009 - Start at 
- 2010 - npm package manager was released 

**NodeJS may not be the best fit:** 
when you have CPU-intensive tasks

# Thinking Asynchronously: 

- Running many processes simultaneously, but separately by different request 
- Multi-Threading(Thread per Client) 
- Event loop - "Single Threaded" - one function is running just one time. when some event is called, each by invoking callback function 

- **Callbacks** generate the **Christmas Tree problem**: 
- **Promises** and **Async/Await** solve this problem 

# Node js. core API is evolving too
- emitter.emit()
- Emmiter.on()
```
emmiter.emit('data', "Hello World!)
emmiter.on('data', (msg) => {
console.log(msg) }) 
```

**Stream** - its a way for streaming data in Node.js, while respecting the asynchronous programming model and event loop 
**Kinds of Streams:** 
- Readable stream  
- Writable 
- Duplicate 

# Modularizing a Node.js Application 
```
const a = require('./a')
module.exports = {b} - function 
module.exports = Customer - class 
```

# How to install node.js 

1. Downloading from the nodejs.org 
2. Package manager :
- MAC: brew install Node.js
- Windows: choco install Node.js
- Linux: use nvm 

The most popular use cases for Node.js is to create web API application 
**Expres**s is a very popular framework for creating web application 

# How to test Node.js Application : 
1. Mocha - test framework 
2. Chai - Assertion Library 
3. Sinon - Spies, Stubs and Mocks 
4. Istanbul - Code Coverage 

# Debugging Node.js App 
1. Printing to the console
2. Debugging option in visual studio code 














