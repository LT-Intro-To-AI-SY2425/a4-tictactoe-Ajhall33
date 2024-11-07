# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
the most difficult part of the programming was the game over function as it by far had the most lines out of any function.
2. Explain how you would add a computer player to the game.
You would add a function that runs afte each of the players turns that would find the best move give a certain board state.
3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
 It would check for any two in a rows of either player in order to block/win and otherwise would make a move to attempt a win. these moves would be center if open and corners if not.