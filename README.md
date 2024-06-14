# Minesweeper Game in Python with Tkinter

This project is an implementation of the classic Minesweeper game using Python and the Tkinter library. The game follows an Object-Oriented Programming (OOP) approach and provides a graphical user interface for a more engaging experience.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [How to Play](#how-to-play)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Graphical User Interface**: Built with Tkinter for a visual gaming experience.
- **OOP Design**: Clean and maintainable code using object-oriented principles.
- **Interactive Gameplay**: Left-click to reveal cells, right-click to flag mines.
- **Dynamic Grid**: Adjust the grid size and mine count through settings.

## Installation
To run this game, you need Python installed on your system. This project does not require any external libraries beyond Tkinter, which comes pre-installed with Python.

1. **Clone the repository**:
    ```bash
    git clone https://github.com/asifurrahmanbubt/Python-Tkinter-Minesweeper-OOP-Based-Game
    cd Minesweeper-Tkinter
    ```

2. **Ensure you have Tkinter installed** (Tkinter is included with standard Python distributions).

## Usage
1. **Navigate to the project directory**:
    ```bash
    cd Minesweeper-Tkinter
    ```

2. **Run the game**:
    ```bash
    python main.py
    ```

## Project Structure
- `main.py`: Initializes the game window and main game loop.
- `cell.py`: Contains the `Cell` class, which represents each cell in the Minesweeper grid.
- `settings.py`: Holds the configuration settings for the game such as grid size and number of mines.
- `utils.py`: Utility functions for calculating grid dimensions.

## How to Play
1. **Start the Game**: Run the `main.py` file to open the Minesweeper window.
2. **Reveal Cells**: Left-click on a cell to reveal it.
3. **Flag Mines**: Right-click on a cell to flag or unflag it as a mine.
4. **Win the Game**: Reveal all non-mine cells to win. If you click on a mine, you lose.

## Contributing
Contributions are welcome! If you have any improvements or suggestions, feel free to fork the repository and create a pull request.

## License
This project is open-source and available under the [MIT License](LICENSE).

