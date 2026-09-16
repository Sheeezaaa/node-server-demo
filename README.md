
# Node.js Server Setup
 Introduction

This project demonstrates the creation of a basic web server using Node.js. The server displays "Hello Javascript" in the browser.

# Step 1: Check Node.js and npm

Node.js and npm were checked using the following commands:

```bash
node -v
npm -v

## Step 2: Create Project Folder
A project folder named node-server-demo was created using:
mkdir node-server-demo
cd node-server-demo

Step 3: Initialize the Project
The Node.js project was initialized using:
npm init -y
This created the package.json file.

##Step 4: Create server.js
A file named server.js was created inside the project folder.
The server uses Node.js's built-in HTTP module.

Step 5: Server Code
The following code was added to server.js:
const http = require('http');

const PORT = 3000;

const server = http.createServer((req, res) => {
  res.writeHead(200, { 'Content-Type': 'text/html' });
  res.end('<h1>Hello Javascript</h1>');
});

server.listen(PORT, () => {
  console.log('Server is running on port 3000');
});

Step 6: Start the Server
The server was started using:
node server.js
The terminal displayed:
Server is running on port 3000


Step 7: Test in Browser
The server was tested by opening:
http://localhost:3000
The browser successfully displayed:
Hello Javascript







