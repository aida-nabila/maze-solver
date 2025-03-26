# Maze Solver

![maze](https://github.com/user-attachments/assets/a854d930-00f2-41a0-aa9d-b8a172f395a2)

## Project Overview
This project is a Python-based maze-solving algorithm that uses search techniques to find a path from the start point **A** to the goal **B**. 
The maze is loaded from a text file, and the program uses a search algorithm to find a solution. The solution can be visualized through both console output and an image file.

## Project Structure
- **maze.py**: The main Python script that implements the maze-solving algorithm and visualization.
- **maze.txt**: An example of a maze file (text format) that the program can solve. The maze consists of walls (#), empty spaces ( ), a start point (A), and a goal point (B).

## **Requirements**
To run the project, you'll need:
- **Python 3.x**: Ensure that Python is installed on your machine.
- **Pillow (PIL)**: Python Imaging Library for generating the maze image. To install Pillow, run: <br>
`pip install pillow`

## How to Run the Script
- Open command-line interface (CLI) or terminal.
- Navigate to the directory containing maze.py.
- Execute the script by providing the maze file as an argument: <br>
`python maze.py maze1.txt`
(Replace maze1.txt with the filename of your maze.)

## Output
- The script will print the maze and the solution (if one exists) in the console.
- A graphical image of the maze with the solution will be saved as maze.png in the current directory.
