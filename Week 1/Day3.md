### JavaScript Fundamentals

✅ variables

- used to store and manipulate data in a program.

✅ if statements

- used to execute a block of code only if a specified condition is true.

✅ loops: for | while

- are a control structure that allows you to repeat a block of code a specified number of times.

- a for loop is used to execute a block of code a specific number of times.

- a while loop is used to execute a block of code as long as a specified condition is true.

✅ functions

- is a block of code that can be defined once and called multiple times. Functions can accept input in the form of arguments, and can return a value as output.

Today's workshop: Password Protected

# ---- PLAN ----

Prompt the user for input - a password in our case.
Store that password in a variable for future use.
Check whether the password matches the correct password: - If it does, reveal the information.

- If it doesn't, let them try again.

- If they fail three times in a row, do not allow them any more tries.

# ---- NEW PLAN ----

Declare a function that will prompt the user for input - a password in our case. In this function, we want to:
Store that password in a variable within the function
Check whether the password matches the correct password:

- If it does, return true from the function.
- If it doesn't, let them try again.
- If they fail three times in a row, do not allow them any more tries, and return false from the function.

console.log a secret only if the function returned true.
