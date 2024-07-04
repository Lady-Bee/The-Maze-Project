MAZE PROJECT

The maze project entails creating a 3D game using raycasting.

TECHNOLOGIES
For this project, these are the technologies that will be used:

Library - SDL2
Language - C programming language
Technique - Ray casting


To start the game

First clone the repo - https://github.com/Lady-Bee/The-Maze-Project.git

Compile all .c files - 
 
gcc -g -Wall -Werror -Wextra -pedantic -I/usr/local/include/SDL2 ./src/*.c -o maze -L/usr/lib/x86_64-linux-gnu -lSDL2 -lm

Run the maze - 

./maze maps/level_1
