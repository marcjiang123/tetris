# Tetris
Tetris game created in Processing for NextCS final project

Made by Marc Jiang and Hui Wang


# Files/Classes:

## Driver:
- Initialize grid in setup
- Update then display grid and shapes.
- Methods to check for if you lost, if there's a full row
- Method to display where the shape will land straight below it

## Grid:
- Generate a grid with a 2d array.
- Will serve as the field for the shapes.

## Shape:
- Construct one out of 7 static shapes.
- Methods to display, move, and rotate it.

# User Interaction:
- interact using mouse and keyboard
- mouse to start the game
- keyboard to control the blocks
  - left arrow to move left
  - right arrow to move right
  - up arrow to rotate
  - z to rotate the other direction
  - down arrow to move the block down faster
  - space to instantly drop the block
  - c to hold the current block and swap with either the block currently being held or the next block
