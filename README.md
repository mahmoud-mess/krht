# Game of Life Simulation

## Overview

Conway's Game of Life is a cellular automaton where cells on a grid evolve based on simple rules of survival, death, and reproduction.

## Rules

1. **Underpopulation**: A live cell with fewer than two live neighbors dies.
2. **Overpopulation**: A live cell with more than three live neighbors dies.
3. **Reproduction**: A dead cell with exactly three live neighbors becomes alive.
4. **Survival**: A live cell with two or three live neighbors remains alive.

## Features

- Toroidal grid with wraparound edges
- Console-based and graphical simulation modes
- Custom initial pattern configurations
- Comprehensive unit testing

## Prerequisites

- C++17 or later
- SFML (Simple and Fast Multimedia Library)
- Google Test (GTest)

## Dependencies

On Debian-based systems, install dependencies:

```bash
sudo apt-get install libsfml-dev libgtest-dev
```

## Build and Run Instructions

### Clone the Repository

```bash
git clone https://github.com/mahmoud-mess/GameOfLife.git
cd GameOfLife
```

### Compilation

Build the project using the Makefile:

```bash
make
```


### Running the Simulation


```bash
./game_of_life
```


### Running Unit Tests

```bash
make test
./test_game_of_life
```