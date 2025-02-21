# Dragon Repeller Game

Welcome to the Dragon Repeller Game! This is a simple RPG game where you must defeat the dragon that is preventing people from leaving the town.

## Game Description

You start in the town square with some initial stats:
- XP: 0
- Health: 100
- Gold: 50
- Inventory: ["stick"]

You can navigate to different locations using the buttons provided:
- Go to store
- Go to cave
- Fight dragon

Each location has different actions you can perform, such as buying health, buying weapons, or fighting monsters.

## How to Play

1. Open `index.html` in your web browser.
2. Use the buttons to navigate through the game.
3. Manage your health, gold, and inventory to defeat the dragon.

## Files

- `index.html`: The main HTML file that contains the game structure.
- `style.css`: The CSS file that styles the game.
- `script.js`: The JavaScript file that contains the game logic.

## JavaScript Functions

### Main Variables

- `xp`: Experience points.
- `health`: Player's health.
- `gold`: Player's gold.
- `currentWeapon`: Index of the current weapon in the inventory.
- `fighting`: Index of the current monster being fought.
- `monsterHealth`: Health of the current monster.
- `inventory`: Array of items in the player's inventory.

### Main Functions

- `update(location)`: Updates the game state based on the current location.
- `goTown()`: Navigates to the town square.
- `goStore()`: Navigates to the store.
- `goCave()`: Navigates to the cave.
- `buyHealth()`: Buys health if the player has enough gold.
- `buyWeapon()`: Buys a weapon if the player has enough gold.
- `sellWeapon()`: Sells the current weapon for gold.
- `fightSlime()`: Initiates a fight with a slime.
- `fightBeast()`: Initiates a fight with a fanged beast.
- `fightDragon()`: Initiates a fight with the dragon.
- `goFight()`: Updates the game state to a fight.
- `attack()`: Handles the attack action during a fight.
- `dodge()`: Handles the dodge action during a fight.
- `defeatMonster()`: Handles the defeat of a monster.
- `lose()`: Handles the player's loss.
- `winGame()`: Handles the player's victory.
- `restart()`: Restarts the game.
- `easterEgg()`: Navigates to the easter egg location.
- `pickTwo()`: Picks the number 2 in the easter egg game.
- `pickEight()`: Picks the number 8 in the easter egg game.
- `pick(guess)`: Handles the number picking in the easter egg game.
