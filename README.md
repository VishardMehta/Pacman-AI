# Pac-Man AI 🎮👻

A Python-based Pac-Man game built using **Pygame**.  
Features smart ghost behaviors with different pathfinding strategies for each ghost.

## Features
- Classic Pac-Man gameplay in a custom grid  
- Ghost AI with distinct movement patterns  
- Clean visuals and smooth controls (Joystick)  

## Ghost Behaviors
- **Blinky (Red)**: Uses **BFS (Breadth-First Search)** – quick and consistent  
- **Pinky (Pink)**: Uses **A\*** with **HeapQ**(Priority Queue) – precise and efficient  
- **Inky (Blue)**: Uses **Simple/Steepest Hill Climbing** – fast but can get stuck  
- **Clyde (Orange)**: Reactive movement – changes path when close to Pac-Man  

Each ghost brings a different level of difficulty and unpredictability.

## How to Run 🕹️

1. Make sure you have Python 3 installed  
2. Install dependencies:  
   ```bash
   pip install pygame
   
3. Run the game:  
   ```bash
   python3 pacman.py
   
