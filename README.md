# Sokoban-Game
Sokoban game implemented with C language.

# What is Sokoban ? 
![sokoban](https://user-images.githubusercontent.com/24523745/92641576-dd6c3200-f2d6-11ea-9e2e-ff337c97e576.jpeg)

# Overview 
![overview](https://user-images.githubusercontent.com/24523745/92642416-73588a80-f2e0-11ea-94c2-270372d80a63.png)

# Compiling and running the game
First of all make sure that the game files and the sprites with 'game-sprites' are in the same directory in your computer.

To compile the game run the following command: 

``` gcc -o main.exe main.c fill.c jeu.c g `sdl-config --libs` -lSDL_image ```

To run the game: 

``` ./main.exe ```

# Requirements 
- SDL 1.2 
- SDL Images 1.2
