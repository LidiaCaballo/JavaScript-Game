> **Disclaimer:** This project was developed as part of a **University of Liverpool** assignment.  
> It is for **educational purposes only** and **must not be copied, reused, or distributed** without permission, in accordance with the University's academic integrity policies.


# Treasure Hunter Game

A simple **grid-based browser game** built with **JavaScript, HTML, and CSS**.  
The player controls a **treasure hunter** on a 5x5 grid, collects treasures, avoids obstacles, and tries to achieve the best **performance index** (score per round).

## Features
- **Setup Stage**: Place treasures, obstacles, and the hunter on the grid.
- **Play Stage**: Move the hunter with **W, A, S, D** keys to collect treasures.
- **Dynamic Gameplay**: New obstacles appear when treasures are collected.
- **Performance Index**: Tracks efficiency (score ÷ rounds played).

## Tech Stack
- **Frontend:** JavaScript, HTML, CSS
- **Assets:** Hunter, obstacle, and treasure images
- **Interaction:** Event listeners for clicks and keyboard movement

## How to Play
1. Open `index.html` in a browser.
2. Place treasures (`5-8`), obstacles (`o`), and a hunter (`h`) during setup.
3. Click **Start Game** and move using:
   - `W` = Up  
   - `A` = Left  
   - `S` = Down  
   - `D` = Right  
4. Avoid obstacles and collect all treasures to maximize your performance index.

## Game End
- Ends when all treasures are collected or the hunter cannot move.
- Performance index is displayed at the end of the game.

