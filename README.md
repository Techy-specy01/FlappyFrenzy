FLAPPYFRENZY 🐦
A Python implementation of the classic Flappy Bird game built with Pygame,featuring smooth gameplay mechanics and pixel-perfect collision detection.


https://github.com/user-attachments/assets/a437d058-94b6-4688-8787-abedae22f3fa




<img width="610" height="801" alt="Image" src="https://github.com/user-attachments/assets/34ea741b-1705-4ba7-89fc-62b70d98cfeb" />
🎮 Overview
FLAPPYFRENZY is a side-scrolling arcade game where player controls a bird navigating through pairs of green pipes. The objective is to fly as far as possible without
colliding with pipes or the ground, earning points for each pipe successfully passed.
The game features classic Flappy Bird mechanics with smooth animations, real-time scoring, and instant restart functionality, all implemented using Python's PYGAME library.

✨Features

Smooth Gameplay: 60 FPS gameplay with fluid bird animations
Dynamic Obstacles: Randomly generated pipe heights for varied difficulty
Real-time Scoring: Live score tracking with visual feedback
Instant Restart: Quick game restart functionality
Collision Detection: Pixel-perfect collision system
Retro Graphics: Classic 2D sprite-based visuals

🎯 Game Rules
Objective
Navigate the bird through as many pipe pairs as possible to achieve the highest score.
Scoring System
+1 Point: Awarded for each pipe pair successfully passed
Game Over: Occurs when the bird collides with pipes, ground, or ceiling
High Score: Track your best performance across sessions

<img width="608" height="800" alt="Image" src="https://github.com/user-attachments/assets/1202c3ad-229c-4ef3-b5a7-36c41b555bb1" />


🚀 Installation
Prerequisites
->Python 3.7 or higher
->Pygame library

Setup Instructions

Clone the repository
bashgit clone https://github.com/yourusername/FLAPPYFRENZY.git
cd FlappyFrenzy

Install dependencies
bash pip install pygame

Verify installation
bashpython --version
pip show pygame


📁 Project Structure
FLAPPYFRENZY/
├── __pycache__/           # Python cache files

│   ├── bird.cpython-313.pyc

│   └── pipe.cpython-313.pyc

├── assets/                # Game assets

│   ├── bg.png            # Background image

│   ├── birddown.png      # Bird sprite (falling)

│   ├── birdup.png        # Bird sprite (flapping)

│   ├── font.ttf          # Game font

│   ├── ground.png        # Ground texture

│   ├── pipedown.png      # Downward pipe sprite

│   └── pipeup.png        # Upward pipe sprite

├── bird.py               # Bird class and mechanics

├── game.py               # Main game loop and logic

└── pipe.py               # Pipe class and generation



🔧 Technical Details
Core Components
game.py-->

Main game loop and state management
Collision detection algorithms
Score tracking and display
Game restart functionality

bird.py-->

Bird physics and animation
Jump mechanics and gravity simulation
Sprite rotation based on velocity
Boundary collision detection

pipe.py-->

Pipe generation and movement
Random height algorithms
Collision boundary definitions
Cleanup of off-screen objects

The project showcases fundamental game development concepts including sprite management, collision detection,
game state handling, and real-time user input processing.
Happy Flying! 🚀


