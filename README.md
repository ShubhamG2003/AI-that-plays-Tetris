# AI that plays Tetris
 
This project implements an AI agent that plays the game of Tetris by automatically determining the optimal placement of tetromino pieces to maximize score and line clears.

## Features
- Evaluates possible moves using heuristic-based scoring
- Optimizes piece placement to clear maximum lines
- Achieves significantly higher scores compared to average human gameplay
- Simulates real-time gameplay using Pygame

## Approach
The AI uses a heuristic evaluation function based on:
- Aggregate height of blocks
- Number of completed lines
- Number of holes
- Surface bumpiness

For each incoming tetromino, all possible positions and rotations are evaluated, and the move with the highest score is selected.

## Tech Stack
- Python
- Pygame
- Heuristic Algorithms

https://github.com/user-attachments/assets/35c38b3a-a589-4af1-9c36-1d45c2476b9b

