# 📘 09 — Mini Projects

**Author:** Sriyut Singh

This is where everything from the earlier folders comes together — small, fun, complete programs that apply loops, conditionals, functions, data structures, and (for the GUI ones) Tkinter, all in one place.

## 📂 What's Inside

| Notebook | What it covers |
|---|---|
| `tic-tac-toe.ipynb` | Console-based Tic-Tac-Toe — board representation, turn-taking, and win-checking logic. |
| `tic-tac-toe-v2.ipynb` | An improved/refactored version of the Tic-Tac-Toe game. |
| `hangman.ipynb` | A Hangman word-guessing game using string/list operations and loops. |
| `snake-game.ipynb` | A basic Snake game implementation. |
| `chess-player.ipynb` | An extensive, guided walkthrough of building a chess-playing program: using the `chess` library, the `Board` class, generating legal moves, a random-move player, a human-vs-computer game loop, and a simple board-evaluation/static-analysis player. |
| `chess-game.ipynb` | A further chess game implementation building on the concepts from Lec 05. |
| `chess-quick-test.ipynb` | A short test/scratch notebook for trying out chess-related code. |
| `bank-game.ipynb` | A simple simulated banking system (deposit/withdraw/balance style program). |
| `atm-system.ipynb` | An ATM simulation — username/PIN check, balance, withdrawal logic. |
| `voice-assistant.ipynb` | A basic voice-assistant style program combining speech/command handling logic. |It is like Jarvis to me.|

## 🧠 Key Concepts Practiced

- Applying loops, conditionals, and functions to build complete programs
- Game logic and state management (Tic-Tac-Toe, Hangman, Snake, Chess)
- Simulated real-world systems (bank account, ATM)
- Working with a third-party library (`chess`) for a non-trivial project
- Basic voice/command-driven program design~ Jarvis Base Prototype

## ▶️ How to Run

```bash
pip install chess
jupyter notebook
```
> `chess-player.ipynb` and the related chess notebooks need the `chess` library. `voice-assistant.ipynb` may need additional packages (e.g. `pyttsx3`, `SpeechRecognition`) depending on what it imports — check the notebook's import cell before running.

---
*Part of the [Python for AI/ML](../README.md) learning series by Sriyut Singh.*
