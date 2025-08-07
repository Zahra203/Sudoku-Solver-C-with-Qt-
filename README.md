# Sudoku-Solver-C-with-Qt-
This project is a GUI-based Sudoku Solver built using **C++ and Qt Framework**, designed to solve 4x4 Sudoku puzzles using a **backtracking algorithm**. The application provides a clean, user-friendly interface where users can input puzzle values, solve the puzzle, or reset for a new one.
## 🎯 Objective
To learn Docker by practically working with containers and images. This includes:
- Installing Docker and Python
- Customizing an image with utilities like `curl`, `git`, and `python3`
- Running a Python script inside a container
- Exposing the container to the host

## ⚙️ Installation

Install the following tools:
- Docker
- Python 3 and pip

## 🛠️ Customization of Docker Image

Added the following to the base image:
- `curl`
- `git`
- `python3` and `pip`

## 🏗️ Building Docker Image

Created a custom Docker image after making modifications inside the running container using:

```bash
docker commit <container_id> student/ubuntu_custom
