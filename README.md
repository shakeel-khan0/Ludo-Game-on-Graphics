# Ludo Game - C++ First Semester Project
By Shakeel Khan

## Project Overview
This is a **Ludo Game** developed in **C++** as my first-semester project. The game uses **graphics** to create a colorful and interactive Ludo board, simulating the classic Ludo gameplay. The project was built without using Object-Oriented Programming (OOP) concepts, focusing more on **functions**, **structures**, and other fundamental C++ concepts.

The game is entirely built using **C++ graphics**, so it is crucial to set up the graphics library in your environment to run the project successfully.

---

## Features
- **Complete Ludo Gameplay**: All basic rules of Ludo are implemented.
- **Graphical Interface**: The game features a graphical Ludo board with dice, tokens, and player movements.
- **Colorful Design**: A wide range of colors is used to enhance the visual experience.
- **Loading Animations**: Loading screens and animations are implemented to make the game feel more dynamic and immersive.
  
---

## Key Concepts
- **Structures**: Used to organize the Ludo game elements like players and their tokens.
- **Functions**: Various functions handle specific tasks like rolling the dice, moving tokens, checking game rules, etc.
- **Graphics in C++**: The game heavily uses graphics functions for rendering the board, tokens, and other visuals.
  
---

## How to Run
1. **Download the required files** (graphics.h, winbgim.h, libbgi.a) and place them in the correct directories for your IDE.
2. **Add the graphics library** to your project:
    - In **Code::Blocks**:
      - Go to `Settings -> Compiler -> Linker Settings`.
      - Add `libbgi.a` to the Link Libraries and set the `Other Linker Options` to:
        ```
        -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
        ```
    - In **Dev C++**:
      - Copy `graphics.h` and `winbgim.h` to the include folder and `libbgi.a` to the lib folder.
      - Go to `Project -> Project Options -> Parameters` and add the following in `Linker`:
        ```
        -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
        ```

3. **Restart your IDE** to ensure the graphics library is configured correctly.

