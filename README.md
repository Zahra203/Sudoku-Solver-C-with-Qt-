## 🧠 Introduction

The goal of this project is to create a Sudoku-solving application that uses a **backtracking algorithm** and provides an intuitive GUI using Qt. It is capable of validating user input and solving incomplete Sudoku puzzles entered by the user.

## ⚙️ Working

- Initializes the application window with Qt
- Accepts user input through a 4x4 grid of text fields
- Solves the puzzle using a backtracking algorithm
- Displays results or warns the user if unsolvable
- Offers "Solve More" and "Exit" options

## 📌 Functional Requirements

- 4x4 input grid (accepts numbers 1–4)
- Solve button (triggers solving)
- Solve More button (resets the grid)
- Exit button (closes the app)
- Error handling for invalid inputs and unsolvable puzzles
- Dynamic memory management to avoid leaks

## 💻 How It Works

1. User inputs the puzzle (leave blank for empty cells)
2. App validates inputs and runs the solver
3. Backtracking logic searches for valid combinations
4. Results are displayed in the same grid
5. Memory cleanup after each solve

## 📤 Output

- Solved Sudoku displayed in the grid
- Pop-up alert for invalid or unsolvable puzzles
- GUI updates dynamically based on button clicks

## 🧰 Technologies Used

- **C++**
- **Qt Framework (Widgets, Layouts, QPushButton, QLineEdit, QLabel)**
- **Backtracking Algorithm**
- **QApplication, QMessageBox, QGridLayout**
