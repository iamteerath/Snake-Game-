# Snake-Game-
This game is built with the programming language C++.
This snake game is a console-based application implemented in C++ that simulates the classic snake game. The player controls a snake, which moves around the screen and grows longer as it eats food. The game features wrap-around mechanics, allowing the snake to reappear on the opposite side when it crosses the screen boundary. The objective is to score points by consuming food while avoiding collisions with the snake's own body. The game employs object-oriented programming principles, with classes representing the snake and the game board, and uses simple data structures like arrays and structs for managing the snake's body and food positions.
Data Structures used : 
(I) Arrays:`body[MAX_LENGTH]`: Used to store the coordinates of the snake's body segments. Each segment is represented as a `Point` object.
(II)Structs: `Point`: Represents a point on the screen with `xCoord` and `yCoord` as its coordinates.
Algorithms:
(I) Movement and Direction Handling: (a) The snake's direction is updated based on user input, and its position is updated accordingly.
                                    (b) Wrap-around logic ensures the snake reappears from the opposite side when it crosses the screen boundary.
(II) Collision Detection: Checks if the snake collides with itself by comparing the head's coordinates with the coordinates of all other segments.
(III) Food Consumption: If the snake's head coordinates match the food's coordinates, the snake grows longer, and new food is spawned.
OOP Concepts used:
(I)Classes and Objects: (a)`Snake`: Represents the snake with attributes like length, direction, and body segments.
                        (b)`Board`: Represents the game board, manages the snake, food, and score.
(II)Encapsulation: Attributes of the Snake class are private, and public methods are used to interact with these attributes.
(III) Inheritance and Polymorphism: Not explicitly used in this code, but could be extended, e.g., creating different types of snakes or food.
(IV) Constructors and Destructors: Used in both Point, Snake, and Board classes to initialize and clean up objects.
(V) Functions: Member functions like move, changeDirection, spawnFood, draw, update, and getInput encapsulate specific behaviors and interactions.
