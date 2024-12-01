# Snake Game (C++ with raylib)

This is a simple Snake game developed in C++ using the **raylib** library as part of a learning project. The game was created by following the tutorial from **Programming with Nick** on YouTube. This project aims to help me learn more about C++ and game development, particularly graphics rendering and game loop mechanics, by utilizing **raylib** for graphics and input handling.

## Features
- Classic Snake game mechanics: Control the snake using the arrow keys, eat food (carrots) to grow longer, and avoid colliding with the walls or the snake's own tail.
- Graphics: The game uses raylib to render the game objects and manage window creation.
- Sounds: The game includes sound effects for actions like eating the carrot and the game over event, similar to the original tutorial.

## Development Process
- **raylib**: The game uses **raylib**, a simple and easy-to-use C library for game development, to handle graphics, window management, and input. It allowed for quick development and focus on game logic.
- **Colors**: The color scheme used in the game was generated with the help of **ChatGPT**, which provided color suggestions to enhance the visual experience.
- **Carrot Image**: The carrot image (`carrot.png`) used in the game was sourced from **OpenGameArt** (a free game asset website). The image was scaled to the appropriate size using **GIMP** for use in the game.
- **Sounds**: The sound effects used in the game were taken directly from the tutorial by **Programming with Nick**, ensuring that the game retains the same audio cues as the original tutorial version.

## Installation

To run the Snake game on your local machine, follow these steps:

### On Linux (Arch Linux):
1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/Beginner_Projects-Snake_Game.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Beginner_Projects-Snake_Game
    ```

3. Make sure you have **raylib** installed. On Arch Linux, you can install it via:

    ```bash
    sudo pacman -S raylib
    ```

4. Compile the game using a C++ compiler (e.g., `g++`):

    ```bash
    g++ -o snake_game main.cpp -lraylib -lm -lpthread -ldl -lrt -lX11
    ```

5. Run the compiled program:

    ```bash
    ./snake_game
    ```

### On Windows:
1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/Beginner_Projects-Snake_Game.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Beginner_Projects-Snake_Game
    ```

3. Download and install **raylib** for Windows:
   - Go to the [raylib website](https://www.raylib.com/).
   - Download the **raylib Windows installer** or follow the [manual installation steps](https://github.com/raysan5/raylib/wiki/Working-on-Windows).
   
   You will need to configure the raylib environment, including linking the raylib library to your project in your IDE.

4. Open your project in your favorite IDE (e.g., **Code::Blocks**, **Visual Studio**, or **CLion**).

5. **Set up raylib in your IDE**:
   - Make sure the raylib headers and libraries are properly linked in your IDE.
   - If you're using **Code::Blocks**:
     - Go to **Settings** > **Compiler** > **Search directories** and add the path to the **raylib** headers.
     - Go to **Settings** > **Linker** > **Link libraries** and add `raylib` as a library.
   - If you're using **Visual Studio**, configure your project settings to link to raylib.

6. Compile the game by building the project in your IDE.

7. Run the compiled program.

### Controls
- **Arrow keys** to control the direction of the snake.
- **Esc** to quit the game.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments
- **Programming with Nick** for the tutorial.
- **raylib** for the game development framework.
- **ChatGPT** for generating the color scheme.
- **OpenGameArt** for the carrot image asset.

---

This is a personal project aimed at learning more about C++ and game development using raylib, and it is not intended for commercial use.
