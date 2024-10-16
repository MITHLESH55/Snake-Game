Snake Game using Object-Oriented Programming (OOP) in C++
This project is a classic Snake game implementation developed in C++ using fundamental Object-Oriented Programming (OOP) concepts. The game lets players control a snake that moves around the console screen, eats food, and grows longer. The game demonstrates core OOP principles such as Encapsulation, Inheritance, Polymorphism, and Abstraction.

Features
Normal Snake Mode: Move the snake to eat food and grow longer.
Fast Snake Mode: Choose a faster snake variant that moves more rapidly.
Score Tracking: Keeps track of the player’s score based on the amount of food eaten.
Real-time Keyboard Controls: Control the snake using W, A, S, D keys for up, left, down, and right directions.
Game Over Detection: Ends the game if the snake collides with itself.
OOP Concepts Used
1. Encapsulation
Encapsulation is demonstrated by grouping related attributes and methods within classes. For example, the Snake class contains the snake’s body, direction, and length, while the Board class manages game updates and rendering.

2. Inheritance
The FastSnake class inherits from the Snake class, reusing its properties and behaviors while adding its own unique functionality, such as faster movement.

3. Polymorphism
Polymorphism is applied by using a base class pointer (Snake*) to handle both Snake and FastSnake objects. The move method in the FastSnake class overrides the one in the Snake class, allowing for dynamic behavior based on the object type.

4. Abstraction
Abstraction is achieved by hiding complex logic behind simple interfaces. The Snake class provides methods like move and changeDirection, and the Board class manages the game loop and input handling without exposing internal details.

Getting Started
Prerequisites
A C++ compiler, such as g++.
A Windows environment (The game uses <windows.h> for console handling).
Compilation & Execution
To compile and run the game, open your terminal and navigate to the project directory. Then, use the following commands:

bash
Copy code
g++ -o SnakeGame SnakeGame.cpp -lconio
./SnakeGame
Controls
W: Move up
A: Move left
S: Move down
D: Move right
How to Play
Run the game executable.
Choose between Normal Snake or Fast Snake by selecting the corresponding option.
Control the snake using the WASD keys.
The game ends if the snake collides with itself.

Created by Adarsh Jha. Feel free to contact me at GitHub: AdarshCodes1221 for any questions or suggestions.

