✅ First support group meeting

- met my support group: Stephanie, Ahs and Damian

- each one of us spoke for 5 minutes about what was going great on the bootcamp and what difficulties we had encountered

- tips: write a comment of what the bug was and how you fixed it

✅ Working with files

- the core file module
- third-party module: uuid
- serialize (JSON.stringify) and deserialize (JSON.parse)

✅ Intro to Express library

- Express is a node js web application framework that provides broad features for building web and mobile applications.

- It is used to build a single page, multipage, and hybrid web application.

- Advantages: - time-efficient - fast - economical - easy to learn - asynchronous

✅ Workshop

// Create a server that prints Hello World

// import the express module and save it in a variable
const express = require('express');
const fs = require("node:fs/promises");

// run the express function and store it in a variable
const app = express();

// set a port, where the server is sending the response
const port = 3000;

let greeting = "";

async function greet() {
const greetJSON = await fs.readFile("./test.json");
greeting = JSON.parse(greetJSON);
return greeting;
}

greet();

// use the get method
app.get('/', (req, res) => {
res.send(
JSON.stringify(greeting)
)
});

app.get('/contact', (req, res) => {
res.send('Contact!');
});

// tell app to listen for a request on the specified port
app.listen(port, () => {
console.log(`Listening on port ${port}`);
});
