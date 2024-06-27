# Snakes N Ladders

## Features

- Multi-client support with up to 4 players.
- Real-time updates of player positions on the board.
- Automatic handling of snakes and ladders.
- Simple and intuitive graphical interface using Pygame.
- Turn-based dice rolling with visual feedback.

## Prerequisites

- Python 3.6+
- Pygame
- Ensure you have the assets `Player_red.png`, `Player_blue.png`, `Player_green.png`, `Player_yellow.png`, and `dice1.png`, `dice_disabled.png` in the `assets` directory.
- Ensure you have the board image `BoardImage.png` in the root directory.

## Installation

Clone the repository:
```bash
git clone https://github.com/yourusername/snakes-and-ladders.git
```
Switch to the correct directory:
```bash
cd snakes-and-ladders
```
Install the required Python packages:
```bash
pip install pygame
```
## Game Controls

- The first player to click the "Start" button will initiate the game when the minimum number of players is connected.
- Players take turns to roll the dice and move their pieces accordingly.
- When a player lands on a snake or ladder, their position is automatically updated.
- The first player to reach position 100 wins the game.
