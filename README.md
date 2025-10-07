[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Tm7PdKHd)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=20864932)
<!-- 
   Assignment Notes:
   - To run the game, execute `python3 nerdle.py` in the terminal.
   - Your task is to implement the equation generation functions in `equation_generator.py` and the solution validator in `game_engine.py`.
   - Don't forget to import your modules.
   - PAY ATTENTION TO THE TODO COMMENTS IN THE CODE.
   - Each function has comments detailing its purpose and requirements.
   - Code is automatically tested *every time* you push changes to GitHub.
-->

# Nerdle 

Nerdle is a fun mathematical twist on Wordle! Instead of guessing words, you need to figure out an 8-character equation like `12+34=46` or `3*34=102`. Put your math skills to the test in this engaging puzzle game.


## Requirements
- Python 3.8 or higher


## Installation
```bash
git clone https://github.com/WTCSC/nerdle-ZoltanHari.git

cd nerdle-ZoltanHari
```

## How to Play

1. Run the Game with the command ``*python3 nerdle.py*`` in the terminal
 
2. Guess the hidden 8-character mathematical equation

## Game Rules
- You have **6 attempts** to guess the correct equation
- Each equation is exactly **8 characters** long 
- Only valid mathematical equations are accepted (+-/*=1234567890)
- Only one operator for every equation (`6*5-2=28` will not work)
- After each guess, you'll get feedback on your numbers and their positions

### Example Equations

![](nerdle1.png)

## Feedback System
Just like Wordle, you'll know what you got right after each guess:
- **Green**: Right number in the right position
- **Yellow**: Right number but wrong position  
- **White**: Number not in the equation

## Decision Tree