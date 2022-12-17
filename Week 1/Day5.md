### First Hackathon

✅ Rock, Paper, Scissors!

Had to build a Rock, Paper, Scissors game using what we learned this week.

🔸 creating a plan
🔸 functions
🔸 if statements
🔸 loops
🔸 arrays
🔸 objects

### Task 1 LOGIC: set of if statements that will determine the winner

1. create a variable for playerMove

2. create a variable for computerMove

3. Draw
   if playerMove(rock) vs computerMove(rock) -> draw
   if playerMove(paper) vs computerMove(paper) -> draw
   if playerMove(scissors) vs computerMove(scissors) -> draw

4. computerMove WINS
   if playerMove(rock) vs computerMove(paper) -> computerMove wins
   if playerMove(scissors) vs computerMove(rock) -> computerMove wins
   if playerMove(paper) vs computerMove(scissors) -> computerMove wins

5. playerMove WINS
   if playerMove(paper) vs computerMove(rock) -> playerMove wins
   if playerMove(rock) vs computerMove(scissors) -> playerMove wins
   if playerMove(scissors) vs computerMove(paper) -> playerMove wins

### TASK 2

1.  put the if ^ statements into a function
2.  write the variables(playerMove, computerMove) as parameters
3.  1= wins; 0=draw; -1 = player1 loses (player2 wins)

### Task 3

1. using a prompt get playerMove value
2. call this function with the result and display in an alert

### Task 4

1. created a function
2. google how to generate a random number Math.random
3. google how to return a hole number - Math.round
4. return the random number
5. assigned rock, paper and scissors to a random number
6. return rock, paper or scissors
7. link the getRandom function with computerMove
8. correct result shows in the alert

### Task 5

1. Use a while loop to play as many times as you like
2. Create a 'Play again?' button using confirm
3. Create if statement for playAgain = true
4. Create if statement for playAgin = false
