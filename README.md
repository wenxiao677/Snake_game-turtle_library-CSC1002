# Snake_game-turtle_library-CSC1002
This program uses python to implement a simple snake game with turtle library.

Turtle library was part of the original Logo programming language developed by Wally Feurzeig, Seymour Papert and Cynthia Solomon in 1967. It is is a pre-installed Python library that enables users to create pictures and shapes by providing them with a virtual canvas. The onscreen pen that you use for drawing is called the turtle and this is what gives the library its name (https://realpython.com/beginners-guide-python-turtle/) . 

This program is the final project of CSC1002(computer laboratory) of CUHKSZ. THe details below are provided by Professor Kinley Lam and TAs.

First, we need to create a game area using the turtle library. The game area is composed of an upper area for statuses and a motion area where the 
snake and monster are moved around, surrounded by a fixed margin along the four sides. The screenshot of the game area is posted in the demo folder. We need to show the motion of the snake (Left, Right, Up, Down, Paused), the elapsed game time in seconds,the total count of body contact of the snake with the monster. Use separate timers to manually refresh the movement of both snake and the monster. 

Sceond, we need to set a timer. When the snake crosses a food item (a number) slow down its movement by increasing its timer rate until its tail is fully extended, that is, the snake will motion slower while the tail being extended.

Third, we need to use the four arrow keys (Up, Down, Left, Right) to maneuver the snake in Up, Down, Left and Right motion respectively. Also, to start up the game, we need to click the screen.

The newest assignment version contains some editions on the food setting. During the game, randomly hide and unhide any unconsumed food items. Use 
appropriate random timer rate, say few seconds between 5 and 10, then randomly pick one of the unconsumed items (including hidden), if the chosen item is visible, hide it, or unhide it otherwise. Hidden food items cannot be consumed by the snake.

For students from the CUHKSZ, please don't just simply copy my codes to finish your homework. If you want to ask me some questions about this assignment, please email me.
