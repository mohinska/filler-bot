# Filler Bot

## Overview

Filler Bot is a Python program designed for a strategy-based game that involves parsing a game field and determining the optimal placement of a figure. The bot uses input data to analyze the field and calculate the best move based on specific conditions, aiming to achieve a strategic advantage.

## Features
- Field Parsing: Reads and processes the game field dimensions and layout.
- Figure Parsing: Extracts the dimensions and shape of the figure to be placed.
- Move Validation: Determines valid positions for placing the figure based on game rules:
- Overlaps exactly one cell of the player’s territory.
- Does not overlap the opponent’s territory.
- Fits within the field boundaries.
- Optimal Move Selection: Chooses the move nearest to the opponent’s cells for a strategic advantage.
- Game Loop: Continuously processes moves until the game ends.

## How It Works
1. Input Parsing:
   - The bot reads input to identify the field dimensions, current field state, and the player’s figure.
2. Move Calculation:
   - It evaluates all possible positions for placing the figure.
   - Valid positions are determined based on the game rules.
3. Optimal Move:
   - From the valid moves, the bot selects the position closest to the opponent’s cells.
4. Output:
   - The bot outputs the chosen move for the player’s turn.
