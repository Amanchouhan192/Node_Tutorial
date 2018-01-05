# Node_Tutorial
this is the tutorial of node js . In Which you can learn the nodejs and apply on the projects..Happy Coding

# About [NodeJS](https://nodejs.org/en/about/)
* **Node.js** is an ``open source`` server ``framework``
* Node.js is ``free``
* Node.js runs on various platforms ```(Windows, Linux, Unix, Mac OS X, etc.)```
* Node.js uses ```JavaScript``` on the server

##  How to ```Install``` Node.js with **NPM** on **Windows**
Follow the step to Install the Nodejs on Windows..
* Open the browser And Type [Nodejs Downlod](https://www.google.co.in/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwjf-fj8zcHYAhWMPI8KHTiNAqEQFggmMAA&url=https%3A%2F%2Fnodejs.org%2Fen%2Fdownload%2F&usg=AOvVaw3mpn_kqKBfLUVM2X6RrMKX)
* And **download** [current version](https://nodejs.org/dist/v9.3.0/node-v9.3.0-x64.msi) of the Nodejs.
* Now check the ```nodejs is install``` or ``not`` open CMD and type **node -v** and it shows the version ``current version`` thats mean the nodejs is install perfectly on your machine
<a href="https://ibb.co/n2WgUw"><img src="https://preview.ibb.co/gFHMUw/amanchouhanwork.png" alt="amanchouhanwork" border="0"></a>
* Now check the [*Node Package Manger(npm)*](https://www.npmjs.com/) is ```install``` or not Repeat above steps and open cmd type **npm -v**.

## Why we use **Nodejs**?
Node.js is a platform built on **Chrome's** [JavaScript](https://www.javascript.com/) runtime for easily building fast and scalable network applications. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.

## How to create Nodejs Server?
* ``create`` the file has **.js** ```extension```.
* type the below code nodejs ***server code***
```js
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
* for start the server type the ***node application name or file name***
<a href="http://www.4GP.ME/bbtc/1515185574612.jpg"><img src="http://www.4GP.ME/bbtc/1515185574612.jpg" border="0" alt="Resim hosting: UploadEdit.com"></a>
* now open the ```browser``` and type in the ``url`` your ```loacl host address``` **hostname = '127.0.0.1'**
software using [visual studio code(vscode editor)](https://code.visualstudio.com)
* And you get your first ```Hello world``` web ```app```
