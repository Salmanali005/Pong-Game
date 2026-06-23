# 🏓 Pong Game

Classic Pong game built in C++ with SFML. Player vs Player and Player vs Bot modes.

## Controls

| Player 1 | Player 2 | Action |
|----------|----------|--------|
| W / S | ↑ / ↓ | Move paddle |
| SPACE | SPACE | Serve ball |

## Features

- 🎮 Two modes: PvP and PvB
- 🏆 High score system (top 10)
- 🔊 Sound effects & menu music
- 🎨 Clean UI with menus

## Build & Run

```bash
# Install SFML (Ubuntu)
sudo apt-get install libsfml-dev

# Build
mkdir build && cd build
cmake .. && make
./pong_game
