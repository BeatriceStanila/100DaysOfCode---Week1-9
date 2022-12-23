Javascript is a synchronous single-threaded language but with the help of event-loop and promises, JavaScript is used to do asynchronous programming

- single-threaded means that contain the execution of instructions in a single sequence => one command is processed at a time.

- synchronous means the code runs in a particular sequence of instructions given in the program.

- each instruction waits for the previous instruction to complete its execution.

<h4>What is asynchronous in JS?</h4>

- due to this nature of synchronous programming, sometimes important instructions get blocked due to some previous instructions, which causes a delay in the user interface.

- asynchronous code execution allows to execution next instructions immediately and doesn't block the flow because of previous instructions.

✅ setTimeout()

🔸 can be used to execute a function or piece of code after a specified amount of time has passed.

🔸 it is often used to schedule the execution of code that needs to be delayed for some reason, such as to give a user time to read a message before it disappears, or to load data from a server before displaying it on a page.

🔸is non-blocking, which means that the code following the setTimeout call will be executed immediately, even if the timeout period has not yet elapsed

✅ workshop: Kayne West quotes API

🔸 made different sorts of HTTP requests (e.g. GET, POST, PUT, PATCH, DELETE)
🔸 used the fulfilled/resolved value of a promise with async/await syntax
