# Number Guessing Game

A command-line number guessing game built with Python.

## Features
- Three difficulty levels — Easy, Medium, Hard
- Unlimited guesses on Easy mode
- 10 guess limit on Medium mode
- 5 guess limit on Hard mode
- Invalid input handling without crashing
- Play again option after each game

## Concepts Learned
- while loops and break statements
- import random and randint()
- Multiple functions with single responsibility
- Nested conditionals
- Counter variables
- None value usage

## How to Run
```bash
python guessing_game.py
```

## Demo
```
=== Number Guessing Game ===

Select Difficulty:
1. Easy   — Unlimited guesses
2. Medium — 10 guesses max
3. Hard   — 5 guesses max
Enter 1, 2 or 3: 2

Enter your guess (1-100): 50
Too high!
Guesses remaining: 9

Enter your guess (1-100): 25
Too low!
Guesses remaining: 8

Enter your guess (1-100): 37
Correct!
You got it in 3 attempts!

Play again? (yes/quit): quit
Thanks for playing. Goodbye!
```
