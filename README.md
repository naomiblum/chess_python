## Chess Python: Interactive Chess Game with Pygame

### 🌟 Overview
- This project is an interactive two-player chess game built using Python and Pygame. 
- It serves as a hands-on exploration of object-oriented programming (OOP) principles, game logic, and animation. 
- The goal of the project is to create a fully functional chess game with a polished user interface and accurate gameplay mechanics.

---

### 🎯 Key Features
- Two-Player Mode: Play chess with a friend on the same device.
- Full Chess Rules: Implements all official chess rules, including:
- Pawn promotion
- Castling
- En passant
- Check and checkmate detection
- Interactive Graphics:
- Highlighting valid moves for selected pieces
- Animations for piece movement
- Modular Design: The codebase is structured using OOP principles for better readability, reusability, and scalability.
- Customizable Assets: Easily replace the graphical assets for a personalized look and feel.

---

### 💡 Objectives
The project was developed with the following goals:

- To practice object-oriented design by modeling chess pieces, the board, and the game's logic as separate classes.
- To deepen understanding of game development using Pygame.
- To simulate a real-world project by integrating logic, graphics, and user interaction.

---

### 🚀 How It Works
- The chessboard is displayed using Pygame, and each square on the board is clickable.
- Players take turns selecting pieces and making moves.
- The game enforces the rules of chess, ensuring that only legal moves are allowed.
- Special game states such as check, checkmate, and pawn promotion are handled automatically.

---

### 📂 Project Structure
The project is organized into multiple files for clarity and reusability:
```
chess_python/
│
├── assets/       # Contains graphical assets for chess pieces
├── board.py    # Handles chessboard logic
├── pieces.py   # Defines chess pieces and their movement rules
├── game.py     # Manages game state and player turns
│── main.py         # Entry point for running the game
```

### ⚙️ Technologies Used
- Python: Core programming language 
- Pygame: Library for game development and rendering graphics

---

### 🛠️ How to Run the Project
Clone the Repository:

```
git clone https://github.com/naomiblum/chess_python.git
cd chess_python
Install Dependencies: Ensure that Pygame is installed:
```

```
pip install pygame
Run the Game:
```

```
python main.py
```

---

### 📝 Future Improvements
Here are some ideas for extending the project:

- AI Opponent: Add a single-player mode with an AI capable of making intelligent moves.
- Online Multiplayer: Enable players to compete over the internet.
- Game Save/Load: Allow saving and loading of game progress.
- Enhanced Graphics: Introduce animations and improved visual effects for a more immersive experience.

---

### 🎨 Visual Preview

<img width="1009" alt="Screenshot 2025-05-06 at 10 17 44 AM" src="https://github.com/user-attachments/assets/10c0fe9a-5252-4132-92a3-299b1cb906bf" />


