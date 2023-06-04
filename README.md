# Game Project 🎮

This is a game project that allows two players to control characters and engage in a battle. The objective of the game is to defeat the opponent player by reducing their health points to zero.

## Game Description

The game features a side-scrolling environment where two players control their respective characters and engage in a battle. The characters can move horizontally, jump, and perform attacks to damage their opponent. The game provides visual feedback, including health bars for each player and an on-screen timer.

## Game Components 🔧

The game project is built using the following components:

- **HTML**: The HTML file (`index.html`) defines the structure of the game page. It includes the game canvas and necessary elements for displaying game information.

- **CSS**: The CSS file (`styles.css`) contains styles and layout rules for the game elements, providing visual aesthetics and responsiveness to the game interface.

- **JavaScript**: The game logic and functionality are implemented using JavaScript. The main JavaScript file (`game.js`) handles player movement, collision detection, health management, game flow, and other game-related operations. The game utilizes the HTML5 canvas element to render the game graphics.

- **Sprites and Images**: The game utilizes sprite sheets and individual images for character animations, background elements, and other graphical assets. These images are stored in the `assets` directory.

- **Utility Functions**: The game includes a utility file (`util.js`) that provides helper functions for collision detection, determining the winner, and managing the game timer.

## Instructions 📝

1. Clone the repository to your local machine. 💻


         https://github.com/Ganeshshinde-2003/Fight_TO_The_Death_Javascript.git
         
         
2. Open the game project in a web browser by double-clicking the index.html file. 🌐

3. The game screen will appear with two characters representing the players. 👬

4. Player 1 controls:

- Move left: Press the 'A' key. ⬅️
- Move right: Press the 'D' key. ➡️
- Jump: Press the 'W' key. ⬆️
- Attack: Press the 'Q' key. 👊

5. Player 2 controls:

- Move left: Press the left arrow key. ⬅️
- Move right: Press the right arrow key. ➡️
- Jump: Press the up arrow key. ⬆️
- Attack: Press the right Ctrl key. 👊
5. Players can move their characters horizontally by pressing the corresponding movement keys. The characters will move left or right accordingly.

6. To make a character jump, press the jump key. The character will perform a jump action.

7. To attack, press the attack key. The character will perform an attack action towards the opponent player.

8. The game continues until one player's health points reach zero. The player with remaining health points wins the game.

9. If the game ends in a tie (both players have the same health points), it will be displayed as a tie result.
