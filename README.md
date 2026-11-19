# Raylib Breakout

A simple Breakout arcade game built with **C++ and Raylib**.

The objective is to destroy all the bricks by bouncing a ball off the paddle without letting it fall off the screen.


## Screenshot

![Gameplay Screenshot](assets/Breakout.png)

## Features

- Classic Breakout-style gameplay
- Paddle movement using keyboard input
- Ball physics and collision detection
- Randomly colored bricks
- Score tracking
- Sound effects for brick and paddle collisions
- Background texture rendering

## Built With

- C++
- [Raylib](https://www.raylib.com/)
- MSYS2 UCRT64
- GCC (g++)

## Controls

| Key | Action |
|---|---|
| Left Arrow | Move paddle left |
| Right Arrow | Move paddle right |

## Download and Play

Download the latest Windows build from the [Releases](../../releases) page.

Extract the ZIP file and run `game.exe`.

## Building from Source

### Requirements

- Windows
- MSYS2 with the UCRT64 environment
- GCC
- Raylib

### Compile

Open the MSYS2 UCRT64 terminal and navigate to the project directory.

Run:

```bash
g++ src/raylib-breakout.cpp -o game.exe -lraylib -lopengl32 -lgdi32 -lwinmm