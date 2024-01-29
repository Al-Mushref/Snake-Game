# Snake Game Example


<img src="snake_game.gif"/>
# Snake Game with Power-ups and Obstacles

This is a classic Snake game implemented in C++ using the SDL library. In addition to the basic gameplay mechanics, the game features power-ups and obstacles to add more excitement and challenge to the gameplay.

## Game Description

The Snake game involves controlling a snake on a grid and guiding it to eat food items, which causes the snake to grow longer. The objective is to achieve the highest score possible without colliding with the boundaries of the grid or the snake's own body.

## Features

The game introduces power-ups that provide unique effects when consumed by the snake. Specifically, a power-up that slows down the snake is spawned after the snake has eaten every five pieces of food. When the snake consumes the power-up, its speed decreases temporarily, allowing the player to maneuver more carefully and strategize their movements.

## Obstacles

To increase the challenge and complexity of the game, obstacles are introduced on the grid. These obstacles are represented by bombs scattered throughout the playing area. If the snake collides with a bomb, it results in a game over. The player must navigate around the obstacles while simultaneously avoiding collisions with the snake's body and the grid boundaries.

## How to Play

Use the arrow keys (up, down, left, right) to control the movement of the snake.
Guide the snake to eat the food items to score points and increase its length.
Avoid collisions with the snake's own body, the grid boundaries, and the bombs (obstacles).
When the snake consumes a power-up, it slows down temporarily, allowing for more precise movements.
The game continues until the snake collides with an obstacle or the player chooses to quit.

## Dependencies for Running Locally

- cmake >= 3.7
  - All OSes: [click here for installation instructions](https://cmake.org/install/)
- make >= 4.1 (Linux, Mac), 3.81 (Windows)
  - Linux: make is installed by default on most Linux distros
  - Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  - Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
- SDL2 >= 2.0
  - All installation instructions can be found [here](https://wiki.libsdl.org/Installation)
    > Note that for Linux, an `apt` or `apt-get` installation is preferred to building from source.
- gcc/g++ >= 5.4
  - Linux: gcc / g++ is installed by default on most Linux distros
  - Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  - Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./SnakeGame`.

## CC Attribution-ShareAlike 4.0 International

The basic structure of the Snake game code is inspired by an example on StackOverflow. The project is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License.

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
