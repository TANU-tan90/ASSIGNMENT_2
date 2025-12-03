This is a simple console-based lane runner game. The player is at the bottom and can move left or right using arrow key. Obstacles fall from the top in random lanes, and the player has to avoid them. If an obstacle reaches the bottom in the same lane as the player, the game ends. How it works : The game keeps running in a loop. First, it checks if the player pressed left or right and moves the player. Then it draws the lanes, obstacles, and player on the screen. The obstacle moves down one step in each loop. If the obstacle reaches the bottom where the player is, the game shows “GAME OVER” and stops. If the obstacle reaches the bottom but the player is not in that lane, a new obstacle comes from the top in a random lane.
The left arrow and right arrow part ensures that the player doesn't cross the 3 lanes

Obstacle movement- The obstacle generates from top with --->obstaclePos = rand() % 3; step = 0; Then it moves down with --->sleep++;

Animation Part - Animation is created using --> system("cls"); Every time each loop ---> 1.Clears screen 2.Then empty rows 3.Generates obstacle in row 4.Put the palyer at bottom

Collision - Collisoin happen only when both the collision conditions are met. It means that --> Obstacle at bottom row and lane is player's lane If both row matches GAME OVER.

Modifications -

Score System, Lives System (Game continues after collision), Difficulty increase.

This is the game analysis from my side that how game works internally,covering all the major points.
I took it as an activity to modify it by adding everything I could to make it more efficient so the initial some loops formatting and other commands were slighty changed to maintain its rhythym with the existing as well as the new modified version of it.
The game is a simple animation in the console using loops and conditions. It helps me understand basic game logic, random numbers, keyboard input, and collision detection.
Hope you enjoy playing it with now added features :) !!! Thanks
