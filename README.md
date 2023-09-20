# 2048_Game


2048 Game Documentation

Introduction:
This document provides documentation for a Python implementation of the popular game "2048." The game is built using the Pygame library.

Table of Contents:
1. Game Setup
2. Colors and Fonts
3. Game Variables
4. Functions
    a. draw_tile
    b. draw_grid
    c. add_tile
    d. move_tiles
    e. is_game_over
5. Game Loop
6. Conclusion

1. Game Setup:
   - The game initializes Pygame and sets up the game window with a specified width and height.
   - The game window is given the title "2048 Game."

2. Colors and Fonts:
   - Several color constants (white, black, gray, red, green, and blue) are defined for drawing elements in the game.
   - Three fonts (font_small, font_medium, and font_large) are defined for displaying text in different sizes.

3. Game Variables:
   - The game is played on a grid with a size of 4x4.
   - Each cell on the grid can contain a numeric value.
   - The grid, tile size, tile margin, and score are initialized.

4. Functions:
   a. draw_tile:
      - Draws a tile with a specified value on the screen.
      - Uses different colors based on the tile's value.
   
   b. draw_grid:
      - Draws the entire game grid by iterating through each cell and calling draw_tile.
   
   c. add_tile:
      - Adds a new tile with a value of 2 to a random empty cell on the grid.
   
   d. move_tiles:
      - Moves tiles on the grid in a specified direction (up, down, left, or right).
      - Handles merging tiles with the same value and updates the score.
   
   e. is_game_over:
      - Checks if the game is over by examining the current grid state.
      - The game is considered over if there are no empty cells and no valid moves left.

5. Game Loop:
   - The game runs in a loop until the player quits.
   - Event handling allows the player to move tiles using arrow keys (up, down, left, right).
   - Tiles are moved, merged, and new tiles are added.
   - The screen is updated with the current grid state and score.
   - If the game is over, a "Game Over" message is displayed.

6. Conclusion:
   - This Python implementation of the 2048 game provides an interactive gaming experience using the Pygame library.
   - Players can make moves to combine tiles and achieve the highest score possible.
   - The game includes functionality to detect game over conditions.

Note: This documentation provides an overview of the code structure and functionality. Detailed code comments can be found within the Python script for a more comprehensive understanding of the implementation.

