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
```markdown
1. Clone the repository:
```sh
   git clone https://github.com/yourusername/snakes-and-ladders.git
```markdown
3. Switch to correct directory:
```sh
   cd snakes-and-ladders
```markdown
5. Install the required Python packages:
```sh
   pip install pygame
```markdown
## Usage

1. Run the server:
```sh
    python3 server.py -host localhost -port 8088
```markdown
2. Run the client:
```sh
    python3 client.py -host localhost -port 8088
```markdown
## Game Controls

The first player to click the "Start" button will initiate the game when the minimum number of players is connected.

Players take turns to roll the dice and move their pieces accordingly.

When a player lands on a snake or ladder, their position is automatically updated.

The first player to reach position 100 wins the game.
