# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# 🎮👾 Tic-Tac-Toe Game

## State in This Application

1️⃣ history → Stores the list of previous board states.
2️⃣ currentMove → Tracks the current turn number.
3️⃣ xIsNext → Determines if X or O should play next.
4️⃣ currentSquares → Gets the board state for the current move.

## Props in This Application

1️⃣ xIsNext → Tells Board whose turn it is.
2️⃣ squares → Provides the current board state.
3️⃣ onPlay → Function to update the board when a square is clicked.
4️⃣ v4️alue={squares[0]} → Passes the current square's value ("X", "O", or null).
5️⃣ onSquareClick={() => handleClick(0)} → Passes the function to update the square when clicked.
