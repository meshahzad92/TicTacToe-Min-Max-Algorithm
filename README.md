# TicTacToe Using AlphaBeta Pruning

![Tic-Tac-Toe](https://img.shields.io/badge/Game-Tic--Tac--Toe-blue.svg) ![Python](https://img.shields.io/badge/Python-3.x-green.svg) ![AI](https://img.shields.io/badge/AI-AlphaBeta%20Pruning-orange.svg) ![License](https://img.shields.io/badge/License-MIT-yellow.svg)

Welcome to **TicTacToe-Using-AlphaBetaPruning**, a sleek Python implementation of the classic Tic-Tac-Toe game featuring an unbeatable AI. This project harnesses alpha-beta pruning—a powerful optimization of the minimax algorithm—to deliver an AI opponent that plays with flawless precision. Can you outwit it, or will you settle for a hard-fought draw?

More than just a game, this repository is a showcase of algorithmic sophistication and clean code design. Whether you’re a developer exploring AI techniques, a student delving into game theory, or simply a fan of strategic challenges, this project offers both entertainment and enlightenment.

---

## 🌟 Features

- **Unbeatable AI**: The AI, driven by alpha-beta pruning, ensures optimal moves—your best outcome is a draw against this master!
- **Interactive Gameplay**: Play as X, entering moves as `row col` (e.g., `0 0`), while the AI (O) responds with calculated brilliance.
- **Move Visualization**: Preview all possible next boards before your turn, enhancing your strategic planning.
- **Modular Design**: Cleanly separated functions for game state, win detection, and AI logic, making it easy to study or extend.
- **Educational Insight**: Perfect for learning about minimax, alpha-beta optimization, and Python programming.

---

## 🎮 How to Play

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/TicTacToe-Using-AlphaBetaPruning.git
   cd TicTacToe-Using-AlphaBetaPruning
   ```

2. **Run the Game**:
   ```bash
   python tic_tac_toe.py
   ```

3. **Gameplay**:
   - You’re Player X (first move).
   - Input moves as `row col` (0-2, space-separated, e.g., `1 1` for center).
   - The AI (Player O) counters with an optimal move.
   - Watch the board evolve—aim for a draw against perfection!

4. **Tips**:
   - Start at the center (`1 1`) for your best shot at a stalemate.
   - Use the move previews to strategize wisely.

---

## 🧠 The AI Under the Hood

The AI’s prowess stems from **alpha-beta pruning**, a refined version of the minimax algorithm:

- **Minimax Foundation**: The classic minimax algorithm explores the full game tree, maximizing X’s score while minimizing O’s, ensuring optimal decisions.
- **Alpha-Beta Enhancement**: Alpha-beta pruning builds on minimax by eliminating branches that can’t influence the final choice, reducing complexity from O(9!) to O(√9!) without sacrificing accuracy.
- **Key Functions**:
  - `minimax(board, alpha, beta, maximizingPlayer)`: Implements the recursive search with pruning logic.
  - `alpha_beta_pruning(board)`: Launches the AI’s move computation.
  - Helpers: `player()`, `actions()`, `result()`, `terminal()`, `utility()`.

This synergy creates an AI that’s mathematically unbeatable—always securing a win or draw, embodying Tic-Tac-Toe’s solved essence.

---

## 📂 Project Structure

```
TicTacToe-Using-AlphaBetaPruning/
├── tic_tac_toe.py    # Main script with game and AI logic
├── README.md         # This file
└── LICENSE           # MIT License
```

---

## 🚀 Installation

**Prerequisites**: Python 3.x

1. Clone the repo (see above).
2. No external libraries needed—just pure Python!
3. Run `python tic_tac_toe.py` to start playing.

---

## 💡 Why This Project Stands Out

- **Algorithmic Brilliance**: Highlights alpha-beta pruning as an elegant optimization of minimax.
- **Code Craftsmanship**: Modular, readable code with clear separation of concerns.
- **Learning Tool**: Offers a hands-on look at game AI and optimization techniques.
- **Strategic Challenge**: Test your skills against an opponent that never falters.

---

## 🤝 Contributing

Want to enhance this project? Contributions are encouraged!

1. Fork the repo.
2. Create a branch (`git checkout -b feature/new-idea`).
3. Commit your changes (`git commit -m "Add new idea"`).
4. Push to your branch (`git push origin feature/new-idea`).
5. Open a Pull Request.

Suggestions:
- Add a graphical UI (e.g., Tkinter, Pygame).
- Create a “beginner mode” with imperfect AI moves.
- Expand to larger grids (e.g., 4x4).

---

## 📜 License

Licensed under the MIT License—see the [LICENSE](LICENSE) file for details. Feel free to use, modify, and distribute!

---


## 🎉 Final Challenge

TicTacToe-Using-AlphaBetaPruning is more than a game—it’s a blend of strategic AI and coding artistry. Play a round, explore the code, and challenge yourself against an algorithm honed to perfection. In Tic-Tac-Toe, a draw is the ultimate victory here—can you claim it?

> “Against an optimized mind, every move is a test. Rise to the challenge!”
