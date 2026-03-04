# F1 Racing Game (Python / Pygame)

A simple **2D racing game** built with **Python** and **Pygame**.  
Choose between 3 cars with different handling, complete laps, track lap times, and avoid collisions.

## Features

- Main menu with car selection:
  - **1** = Red Car (fast)
  - **2** = Blue Car (balanced)
  - **3** = Orange Car (slower)
- Lap timer:
  - shows **Current Lap**
  - stores and displays **Last Lap** (after at least 2 laps)
- Reset button (mouse click)
- Collision detection using **masks**:
  - track limits (slowdown)
  - decoration (strong slowdown)
  - walls (reset)
- Speed display (km/h approximation)

## Controls

- **W**: accelerate forward  
- **S**: brake / reverse  
- **A / D**: rotate left / right  
- **ESC**:
  - from game → back to menu
  - from menu → exit
