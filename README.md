# 🧩 Sudoku Generator & Solver

This Python project generates a Sudoku puzzle with a valid randomized board and solves it using a backtracking algorithm.

---

## 📋 Features

- ✅ Generates a complete, valid Sudoku board
- ❌ Randomly removes values to create a playable puzzle
- 🧠 Solves the puzzle using recursion & backtracking
- 🎯 Adjustable difficulty by setting how many numbers to pre-fill

---

## 🛠 How It Works

### `generate_board(num)`
- Generates a full, valid 9x9 Sudoku board.
- Randomly removes cells based on `num` (number of pre-filled values).
  - `num = 0` → hard (about 25% filled)
  - `num = 81` → full board (nothing to solve)

### `solve(board)`
- Solves the board using a classic backtracking algorithm.
- Fills empty cells with valid numbers recursively.

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

