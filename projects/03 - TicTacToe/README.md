# Project: Tic-Tac-Toe

This project demonstrates how you might use a **single-dimensional array** in C# to store information in a grid-based game like ***Tic-Tac-Toe*** .  In this case a 9 element array is used to store the 9 possible positions of the tic-tac-toe game.  The players of the game indicate which position they would like to play in, using the following numbering system as a guide.

|   |   |   |
| :-------------: | :-------------: | :-------------: |
| 1 | 2 | 3 |
| 4 | 5 | 6 |
| 7 | 8 | 9 |


## Note:  Using Single-Dimensional Arrays in C#

Click [here](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/arrays/single-dimensional-arrays) to get more detailed information about how to use single-dimensional arrays in C#.

# Task:

At the moment this project will detect a **Win!** in the ***top row*** only and end the game by declaring the winner.  However, there are 8 possible win conditions in Tic-Tac-Toe.  You task is to,

1.  Modify the **GameOver()** function so that it detects a win using all the 8 possible win conditions.
2.  Complete the **GameOver()** function by adding code that will detect a tie, end the game, and declare the **Tie!**.
