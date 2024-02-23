# AI-Enhanced Pong Game with Fuzzy Logic

## Overview
This project is an advanced implementation of the classic Pong game, featuring an AI opponent driven by fuzzy logic. The game is built in Python using the Pygame library and the Scikit-Fuzzy package for fuzzy control system development.

## My Contribution: FuzzyPlayer Class
My main contribution to this project is the development of the `FuzzyPlayer` class, which uses fuzzy logic for decision-making. This class enhances the game by controlling the paddle's movement in a more sophisticated manner compared to traditional methods.

### Features of FuzzyPlayer:
- Utilizes fuzzy control rules to determine paddle movement based on the ball's position.
- Implements membership functions for input variables (horizontal and vertical distances) and output variable (paddle velocity).
- Defines rules for paddle control using fuzzy logic, allowing for nuanced reactions to the ball's movement.

## Installation and Usage
To run the game, ensure you have Python, Pygame, and Scikit-Fuzzy installed. Clone the repository and execute the main script to start the game.

```bash
pip install pygame
pip install -U scikit-fuzzy
python main.py
