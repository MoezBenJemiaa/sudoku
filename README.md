# 🧩 Sudoku Generator & Solver

This Python project generates a valid Sudoku puzzle with a randomized board, then solves it using a recursive backtracking algorithm.

---

## 📋 Features

- ✅ Generates a full valid Sudoku board
- 🔀 Randomly removes cells to create a puzzle
- 🧠 Solves the puzzle using backtracking
- 🎯 Adjustable difficulty by controlling how many numbers are pre-filled

---

## ▶️ Run the Program

1. **Clone the repo** or download the Python file.
2. Make sure you have **Python 3.x** installed.
3. Run the script:

```bash
python sudoku.py
```

You will see:

- A fully generated board.
- A playable puzzle with empty cells.
- The solved version of the board.

---

## 📂 File Structure & Key Functions

| Function           | Description                                                              |
|--------------------|---------------------------------------------------------------------------|
| `generate_board(num)` | Generates and masks a Sudoku board based on difficulty                 |
| `print_board(board)`  | Prints the board in a readable grid format                             |
| `possible(board, pos, num)` | Checks if placing a number is valid for the given position       |
| `next_empty(board)` | Finds the next empty cell to be filled (i.e., contains a 0)             |
| `solve(board)`       | Uses recursion and backtracking to solve the puzzle                    |

---

## 🧪 Example Output

```bash
=======full board========
5 3 4 | 6 7 8 | 9 1 2
6 7 2 | 1 9 5 | 3 4 8
1 9 8 | 3 4 2 | 5 6 7
- - - - - - - - - - - - -
8 5 9 | 7 6 1 | 4 2 3
4 2 6 | 8 5 3 | 7 9 1
7 1 3 | 9 2 4 | 8 5 6
- - - - - - - - - - - - -
9 6 1 | 5 3 7 | 2 8 4
2 8 7 | 4 1 9 | 6 3 5
3 4 5 | 2 8 6 | 1 7 9

======solvable board=====
5 0 0 | 6 0 0 | 0 1 0
0 7 2 | 0 9 0 | 3 0 0
...
```

---

## 🔮 Future Ideas

- 🎨 Add a graphical user interface using Tkinter or Pygame
- 🧩 Add support for selecting difficulty levels (easy, medium, hard)
- 🧪 Implement a Sudoku board validator
- ⏱ Add a timer and scoring system for players
- 🌍 Export puzzles to files or share online

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).  
Feel free to use, modify, and distribute it as you like.

---

### Made with ❤️ in Python
