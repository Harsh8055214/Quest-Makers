# Snake Game in C++
# Quest Makers
## Description
This is a simple console-based Snake game implemented in C++. The game features a moving snake that grows in length each time it consumes a fruit. The game ends when the snake collides with the walls or itself.

## Features
- Move the snake using `W`, `A`, `S`, `D` keys.
- Eat fruits to increase the score.
- The snake grows longer as it eats fruits.
- Game over occurs when the snake collides with the walls or itself.
- Score tracking.

## How to Run
### Prerequisites
- A C++ compiler (such as g++ or MSVC)
- Windows OS (as it uses `conio.h`, `windows.h`)

### Compilation
To compile the game, use a C++ compiler such as g++:
```sh
 g++ snake.cpp -o snake.exe
```

### Running the Game
```sh
 ./snake.exe
```

## Controls
- `W` - Move Up
- `S` - Move Down
- `A` - Move Left
- `D` - Move Right
- `X` - Exit the game

## Code Explanation
- **Setup()**: Initializes game variables, including snake position and fruit placement.
- **Draw()**: Renders the game board in the console.
- **Input()**: Captures user input for movement.
- **Logic()**: Updates the snake's movement, detects collisions, and manages fruit collection.
- **main()**: Runs the game loop until `gameOver` is true.

## Dependencies
- `<iostream>`: For input/output operations.
- `<conio.h>`: For capturing keyboard input.
- `<windows.h>`: For sleep function and clearing the console.

## Future Enhancements
- Implement boundary-less movement (snake appears on the opposite side when hitting a wall).
- Add difficulty levels.
- Improve graphics using a GUI library.

## License
This project is open-source and free to use.

## Author
Developed by:-
Kodavala Harsh - 202401121
Harsh Panchal - 202401134
Krisha Bhuva - 202401099
Krishna Parmar-202401100

