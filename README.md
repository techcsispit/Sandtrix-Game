# Sandtrix Clone

## About
This is a clone of the original game [SANDTRIX](http://sandtrix.net/) made in Python. All game logic is original except for the basics of block spawning, which follow a Tetris tutorial. The game is still a work in progress and not fully complete.

## Requirements

Make sure you have the following installed:
- Pygame
- NumPy

### Installation
Run the following command to install the required packages:
```
pip install pygame numpy
```

## Broken Things to be Fixed:
- [ ] Out of bound errors in path-finding algorithm - There's an issue with blocks moving outside of the intended play area.
- [ ] Sand clearance mechanism - Implement a mechanism to clear sand and gain points.
- [ ] Game over mechanism - Include proper game-over logic and allow the game to reset after.
- [ ] Next block shape and color display - Display the next block’s shape and color in a side panel for better player experience.

## Things to be Added:
- [ ] Proper game UI interactive with mouse - A fully functional user interface that responds to mouse inputs.
- [ ] Background music and sound effects - Add background music and game sounds for more immersion.
- [ ] Game start screen with title and art - Create a visually appealing start screen with game title and artwork.
- [ ] Game special effects - Introduce visual effects to enhance gameplay, like animations or particle effects.
- [ ] Some power-ups - Add power-ups that give players unique advantages during gameplay.

## Usage

1. Clone the repository and navigate to the project directory:
   ```
   git clone https://github.com/techcsispit/Sandtrix-Game
   cd Sandtrix-Game
   ```
2. Install the dependencies:
   ```
   pip install pygame numpy
   ```
3. Run the game:
   ```
   python src/game.py
   ```

## Contributing
We welcome contributions to the project. Please feel free to submit bug fixes, improvements, and features via pull requests.

1. Creating an Issue: Before making any changes, create an issue explaining what you'd like to add or change and why
2. Fork the repository.
3. Create a new branch for your feature or bug fix.
4. Commit your changes and push the branch.
5. Submit a pull request.

## Raising an Issue
If you encounter any bugs or would like to request a feature, please create an issue on the repository with detailed steps to reproduce or a description of the feature request.
