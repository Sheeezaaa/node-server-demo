
# Node.js Server Setup
 Introduction

This project demonstrates the creation of a basic web server using Node.js. The server displays "Hello Javascript" in the browser.

# Step 1: Check Node.js and npm

Node.js and npm were checked using the following commands:

```bash
node -v
npm -v
​```
## Step 2: Create Project Folder
A project folder named node-server-demo was created using:
```bash
mkdir node-server-demo
cd node-server-demo
```
### Step 3: Initialize the Project
The Node.js project was initialized using:
npm init -y
This created the package.json file.

## Step 4: Create server.js
A file named server.js was created inside the project folder.
The server uses Node.js's built-in HTTP module.

## Step 5: Server Code
The following code was added to server.js:
```bash
const http = require('http');

const PORT = 3000;

const server = http.createServer((req, res) => {
  res.writeHead(200, { 'Content-Type': 'text/html' });
  res.end('<h1>Hello Javascript</h1>');
});

server.listen(PORT, () => {
  console.log('Server is running on port 3000');
});
```
## Step 6: Start the Server
The server was started using:
node server.js
The terminal displayed:
Server is running on port 3000


## Step 7: Test in Browser
The server was tested by opening:
http://localhost:3000
The browser successfully displayed:
```bash
Hello Javascript
```

<img width="1122" height="850" alt="adv1" src="https://github.com/user-attachments/assets/665b2eda-4a00-4cd6-b755-e212f6a0f891" />
<img width="545" height="209" alt="ad5" src="https://github.com/user-attachments/assets/08799387-faeb-4a07-b1b9-8479457f89ae" />

<img width="599" height="303" alt="image" src="https://github.com/user-attachments/assets/e7afaaf9-0fe0-4198-8eb2-baafd1ad5bb5" />
<img width="738" height="516" alt="ad 3" src="https://github.com/user-attachments/assets/db12d493-76fe-4a8f-8163-c52443da4215" />












