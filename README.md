# Sudoku Solver

## Project Overview

This project is a Sudoku Solver that uses a combination of OpenCV and a Convolutional Neural Network (CNN) to extract and solve Sudoku puzzles from images. The notebook (`solver.ipynb`) demonstrates the process of image preprocessing, digit recognition, and solving the Sudoku puzzle.

## Features

- **Image Processing:** Uses OpenCV to preprocess Sudoku puzzle images.
- **Digit Recognition:** A Convolutional Neural Network (CNN) trained to recognize digits from the Sudoku grid.
- **Puzzle Solving:** Solves the Sudoku puzzle using a backtracking algorithm.

## Setup and Installation

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - TensorFlow/Keras
  - OpenCV
  - NumPy
  - Matplotlib

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/Chetan7595/Sudoku-Solver.git
   cd sudoku-solver
   ```

2. Install the required Python packages:

   ```
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```
   jupyter notebook solver.ipynb
   ```

### Usage

1. Load an Image: Provide an image of a Sudoku puzzle.
2. Preprocessing: The image will be processed to extract the Sudoku grid.
3. Digit Recognition: The CNN model will recognize the digits in the grid.
4. Solve the Puzzle: The Sudoku puzzle will be solved, and the solution will be displayed.
