# Where Battle Ship is Hidden

A console-based Battleship game developed using Python.

## Project Description

This project simulates a simple battleship game where the player attempts to locate and destroy a hidden enemy battleship by guessing its coordinates.

The battleship position is randomly generated, and the player has limited attempts to find it.

## Features

- Random battleship generation
- Dynamic game board creation
- User input validation
- Win/Lose conditions
- Hint messages
- Console-based interface

## Technologies Used

- Python 3
- Random module

## How to Run

Clone the repository:

bash
git clone https://github.com/Bhanu-2907/Where-Battel-Ship-is-Hidden.git


Move to project folder:

bash
cd Where-Battel-Ship-is-Hidden


Run the program:

bash
python battleship_game.py


## Example Output

```text
O O O O
O O O O
O O O O
O O O O
```
Enter guessed row: 2
Enter guessed col: 3

#for every worng guess by user. The guessed_row and guessed_column will marked "X"
```text
O O O O
O O X O
O O O O
O O O O
```
That was a close shot but not good enough.

#The user guess is correct, pattern will not be printed in output 
Output: "Congratulation! You desotryed the enemy battelship"

## Future Improvements

- Multiple battleships
- Difficulty levels
- Score system
- Colored output
- Multiplayer mode

## Author

Bhanu Prakash
