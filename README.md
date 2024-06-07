# Candy Crush in 8086 Assembly

This project is an implementation of the Candy Crush game in Assembly language. It follows the typical gameplay of swapping adjacent candies to create matches and clear the board. The game consists of multiple levels with varying board shapes and challenges.

## Overview

The game is split into levels, each with its own unique board layout and challenges. Here's a brief overview of each level:

### Level 1
- Displays the game title and rules.
- Features a 7x7 game board filled with random candies.
- Supports candy swapping to create matches and clear combos.
- Introduces a color bomb that destroys all occurrences of a specific candy when swapped.

### Level 2
- Features a different shape board with similar gameplay mechanics to Level 1.
- Presents new challenges with varying board layouts and candy shapes.

### Level 3
- Similar board shape to Level 1 but with restricted row and column movements.
- Adds additional challenge by blocking certain movements on the board.

## Scoring and Moves

- Players earn points based on the size of combos created during candy crushing.
- Explosions also award points based on the number of occurrences destroyed and their location.
- Each level provides the player with 15 moves to complete the objectives.
- Players must reach a threshold score to clear each level; otherwise, they are prompted to try again.

## File Handling

- Individual level scores are saved in a file.
- The file stores the highest score and player name.
- Data is recorded in a specific format for easy retrieval and display.

## Bonuses

- Restricts the mouse cursor within the board boundaries for a seamless gaming experience.
- Highlights exploding rows/columns before initiating the explosion.
- Reverts candy swaps if no combo exists after the swap.
- Enhances the visual appearance of Level 3 with a changed background.
- Displays text prompts such as "crushing" during combo actions and "explosion" during bomb usage.

## Files

- **game.asm**: Contains the main game code.
- **utilities.inc**: Includes utility functions used in the game.
- **letters.inc**: Stores the code for displaying letters on the starting page.
- **candies.inc**: Includes the design code for various candies used in the game.

## Running the Game

This game is developed in Assembly language and can be run using an 8086 emulator or simulator.

