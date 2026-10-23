# SE Lab 4 – Fishing Game

## Student Details
- **Name:** Bhavin G Kamat
- **SRN:** PES1UG24AM065
- **Subject:** Software Engineering

## Project Description
The Fishing Game is a Python game developed using Pygame. The player controls a fishing hook to catch fish and earn points within a limited time.

## Features
- Hook and fish collision detection.
- Multiple fish types with different speeds and point values.
- Player-controlled casting using the Spacebar.
- A 30-second game timer.
- Score tracking and a game-over screen.
- Restart functionality using the R key after the game ends.

## Technologies Used
- Python 3.13
- Pygame

## Project Structure
```text
SE-Lab-4/
├── game/
│   ├── catch.py
│   ├── fish.py
│   ├── game_engine.py
│   ├── hook.py
│   └── renderer.py
├── main.py
├── test_catch.py
└── README.md
```

## Setup and Execution

### 1. Install Python
Install Python 3.13 if it is not already installed.

### 2. Install Pygame
```bash
py -3.13 -m pip install pygame
```

### 3. Run the game
```bash
py -3.13 main.py
```

### 4. Run the catch-detection tests
```bash
py -3.13 test_catch.py
```

## Controls
- **Spacebar:** Start a fishing cast.
- **R:** Restart after the game ends.
- **Close window:** Exit the game.

## Lab Evidence

### Before Fix
[Watch the BEFORE video](evidence/before.mp4)

Shows the original game behavior before the bug fix.

### After Fix
[Watch the AFTER video](evidence/after.mp4)

Shows the corrected catch-detection behavior and implemented game features.

### ChatGPT Conversation
[View the full ChatGPT conversation](PASTE_YOUR_CHATGPT_CONVERSATION_LINK_HERE)
