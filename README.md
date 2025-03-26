# TetrisGAME
This is a simple Tetris game implemented in C++ using `ncurses` for terminal-based rendering.

## Features
- Classic Tetris gameplay
- Smooth piece movement and rotation
- Collision detection
- Scoring and level progression
- Fast drop and game over detection

## Requirements
Ensure you have the following installed before compiling the game:

- A C++ compiler (e.g., g++)
- `ncurses` library

## Installation
Clone the repository:
```sh
git clone https://github.com/yourusername/tetris-game.git
cd tetris-game
```

## Compilation
Compile the game using g++:
```sh
g++ tetris.cpp -o tetris -lncurses -pthread
```

## Usage
Run the game with:
```sh
./tetris
```

## Controls
- **Left Arrow**: Move piece left
- **Right Arrow**: Move piece right
- **Down Arrow**: Move piece down faster
- **Space**: Hard drop
- **Z**: Rotate piece
- **Esc**: Quit game

## Preview
```
################
#              #
#     A        #
#     A        #
#     A        #
#     A        #
#              #
################
```

## License
This project is licensed under the MIT License. Feel free to modify and distribute!

## Author
- **Your Name** - [GitHub](https://github.com/yourusername)
