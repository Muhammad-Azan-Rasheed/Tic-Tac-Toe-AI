
# Tic-Tac-Toe AI — System Architecture

## 1. Project Overview

This project is a full-stack Tic-Tac-Toe game.
A human player plays against an AI opponent.

## 2. System Components

### Frontend (React)
- Displays the game board.
- Accepts player moves.
- Shows game results and scores.
- Communicates with the backend using REST APIs.

### Backend (Python Flask)
- Receives requests from the frontend.
- Manages game logic.
- Validates player moves.
- Communicates with the AI algorithm.

### AI Engine (Minimax)
- Evaluates possible moves.
- Selects the best available move.
- Tries to win or prevent the player from winning.

## 3. Communication Flow

1. Player selects a cell on the React interface.
2. React sends the move to the Flask backend.
3. Backend updates the game state.
4. Minimax calculates the AI's best move.
5. Backend sends the updated board to React.
6. React displays the updated game.

## 4. Technology Stack

| Component | Technology |
|---|---|
| Frontend | React.js |
| Build Tool | Vite |
| Backend | Python Flask |
| AI Algorithm | Minimax |
| Communication | REST API |
| Version Control | Git and GitHub |

## 5. Data Storage

The initial version will not use a database.
Game state and scores will be managed during the application session.

## 6. Future Improvements

- Improved user interface.
- Different AI difficulty levels.
- Persistent score storage.
