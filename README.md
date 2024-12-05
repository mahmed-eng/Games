# Space Invaders Game
This is a classic Space Invaders game built using HTML5, CSS, and JavaScript. The game allows players to control a spaceship, shoot bullets, and destroy incoming enemies in a retro space shooter style.

## Features
Player Spaceship: Move left and right, shoot bullets with the spacebar.

## Enemy Spaceships: 
Move downward, spawn randomly, and can be destroyed by bullets.

## Collision Detection: 
Collisions between bullets and enemies increase the score, while colliding with an enemy ends the game.

## Score: 
Displays the player's score based on the number of enemies destroyed.

## Game Over: 
The game ends when an enemy collides with the player's spaceship.

## Background:
Animated stars for a dynamic space environment.

## How to Play
Use the left and right arrow keys to move the spaceship.
Press Spacebar to shoot bullets upwards.
Destroy enemy ships to increase your score.
Avoid enemy ships from colliding with your spaceship.

## Controls
### Arrow Left: 
Move the spaceship left.
### Arrow Right: 
Move the spaceship right.
### Spacebar: 
Shoot bullets.

## Installation
Clone or download the repository to your local machine.
Open the index.html file in a web browser.
The game will automatically start.

## Technologies Used
### HTML5:
Used for structuring the game page and the Canvas element.

### CSS3: 
Used for styling the page, including the background and game-over screen.

### JavaScript: 
Handles game logic, including player movement, shooting, enemy spawn, collision detection, and score tracking.

## Game Logic Breakdown
### Player Movement: 
The player can move left and right across the bottom of the screen using arrow keys.
### Bullet Movement: 
Bullets are fired upwards when the spacebar is pressed and disappear once they move off the screen or hit an enemy.
### Enemy Spawn: 
Enemies spawn randomly at the top of the screen and move downwards. If they reach the bottom, they are removed.
### Collision Detection: 
If a bullet collides with an enemy, both the bullet and enemy are removed, and the score increases. If an enemy collides with the player, the game ends.
### Score: 
The score increments by 1 for each enemy destroyed.

## Game Over
When the game ends (i.e., when an enemy collides with the player), a "Game Over" message will appear with a button to restart the game.

## Screenshots
![Game Screenshot](Games/Screen Shots/0.jpg)


## License
This project is open source and available under the MIT License.

## Acknowledgements
Thanks to HTML5, CSS3, and JavaScript for their versatility in creating browser-based games.
Inspired by the classic Space Invaders game.
