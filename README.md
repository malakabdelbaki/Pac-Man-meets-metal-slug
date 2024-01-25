# Console Shooter Game: Pac-Man-meets-metal-slug

Welcome to Heroic Showdown, a console-based 2D shooter game that seamlessly fuses the excitement of Pac-Man and Metal Slug. Your mission is to navigate through a 15x15 grid, vanquishing monsters and emerging victorious. Choose your hero wisely, select your weapons strategically, and dive into the pixelated battlefield!

## Features:

### Heroes: The player controlled character

1. **MedicHero:**
   - can only wield 1 weapon
   - Special Ability: Self-heal once during the game

2. **DemolitionHero:**
   - can wield 2 weapons simultaneously
   - Special Ability: Switches freely between them

### Actions for Any Hero:

1. **Move:**
   - 'w' for up, 's' for down, 'd' for right, 'a' for left.

2. **Shoot:**
   - Choose a direction to shoot the hero's gun.

3. **Weapon Special Ability:**
   - Activate the gun's unique special ability.

4. **Hero Special Ability:**
- Activate the hero's unique special ability.

### Weapons:

1. **Pistol:**
   - Bullets: 16
   - Range: 2
   - Damage: 30
   - Special Ability: Fire a bullet in all four directions.

2. **Bazooka:**
   - Bullets: 4
   - Range: 8
   - Damage: 150
   - Special Ability: Eliminate all enemies in the same diagonal across the map.

3. **Rifle:**
   - Bullets: 30
   - Range: 4
   - Damage: 20
   - Special Ability: Fire three rounds (left, right, and up), penetrating monsters within the range.

### Monsters:

1. **GhostMonster:**
   - Disappears every 3 turns for 3 turns, then reappears.

2. **TankMonster:**
   - Has a shield that absorbs damage before the monster is attacked.

### Items:

1. **Ammo:**
   - Collect bullets to replenish ammunition.

2. **Potion:**
   - Collect health potions for healing.

## Game Flow:

1. Initialize a 15x15 grid with health potions, ammo, and monsters.
2. User selects hero and corresponding weapons.
3. Game starts, displaying hero info, round number, and the visual map.
4. Battle monsters, collect items, and survive.

## End Scenarios:

- **Loss:**
  - Hero is defeated.

- **Win:**
  - All monsters are vanquished from the grid.
 
## Implementation
- Implement the class Object, from which all other classes are derived.
- Implement the class Character, from which Hero and Monster are derived.
- Implement the class Gun and its derived classes.
- Implement the class Item, and its derived classes.
- Implement the class Game, which represents the grid.
- Operator overloading for display and interactions between hero and other elements of the game.
- Implement methods to apply game logic and special abilities
- Manage game flow, rounds and update map dynamically.

  
Get ready for a thrilling adventure in Heroic Showdown. Choose your hero, load your weapons, and let the battle begin! 🕹️💥
