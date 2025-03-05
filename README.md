
# Tic-Tac-Toe with Tkinter 🎮

Welcome to this Python-based Tic-Tac-Toe game using Tkinter! 🐍✨ This project walks you through creating a simple yet fun GUI game where two players can compete against each other on a 3x3 board. 🤜🤛

The board is displayed in a graphical window using the Tkinter library, a standard Python module for building GUI applications. 🖥️

![Welcome](assets/playing.gif)

## Game Features 🌟
- Two-player gameplay: Players take turns marking X and O on the grid. 🤠❌
- Graphical Interface: A simple, intuitive GUI built using Tkinter. 🖼️
- Game Reset: After a game is won or ends in a draw, you can restart the game easily. 🔄
- Win Detection: The game automatically detects when a player wins or when there's a draw. 🏅

## The Game Board
We represent the game board as a 3x3 grid, where each cell can either be empty, contain an X, or contain an O. The Tkinter Button widget is used to create clickable cells. ⬛⬜

## The Tkinter Interface
- Tkinter’s Button widget is used to create the 3x3 grid. Each button represents a cell in the Tic-Tac-Toe grid. 📲
When a button is clicked, the command is triggered to update the button with either "X" or "O". ❌⭕
- The Label widget is used to display messages like "Player X's turn" or "Player X won !" or "Tie Game" 📢
## Run Locally

Clone the project

```bash
  git clone git@github.com:emilours/Tic-Tac-Toe.git TIC_TAC_TOE
```

Go to the project directory

```bash
  cd TIC_TAC_TOE
```

Install dependencies

```bash
  python -m tkinter
```

Start the game
```bash
  python tic_tac_toe.py
```

