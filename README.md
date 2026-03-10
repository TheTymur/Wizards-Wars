# Wizards War

## Intro
Wizards War is a 2D turn-based battle game developed using Python and Pygame. The game pits two players against each other in an epic magical showdown. Players assume the roles of wizards, each equipped with health, mana, and a set of powerful spells. The goal is to outmaneuver and outlast your opponent by strategically managing resources, casting spells, and exploiting opportunities to claim victory.

## Technologies and tools used for this project:
- **Language:** Python
- **Library:** Pygame (for graphics and event handling)
- **Graphics:** Open-stock images to enhance the atmosphere and real-time animations for spell effects.
- **Architecture:** Modular code structure for easy addition of new spells or gameplay features.
- **State Management:** Global variables and standard control flow.

## Features
- **Turn-Based Combat:** Players alternate turns to choose from a variety of spells, each with unique effects, costs, and strategies. Intuitive mechanics like poison damage, health recovery, and mana regeneration add depth to each turn.
- **Spell Arsenal:**
  - *Fireball:* Deal direct damage at a moderate mana cost.
  - *Water Orb:* Higher damage output with increased mana cost.
  - *Poison:* Inflict damage over time for sustained pressure.
  - *Recovery:* Regenerate mana to prepare for future attacks.
  - *Sleep:* Restore health at the cost of skipping a turn.
- **Strategic Elements:** Players must manage their health and mana wisely, balancing offense and defense. Status effects like poison and sleep introduce layers of strategy.
- **Visual Status Tracking:** A dynamic health and mana bar system visually represents each player’s status.
- **Info Menu:** A handy in-game guide provides detailed information on spells and gameplay mechanics.

## Gameplay Mechanics
- Players start with equal health and mana and take turns casting spells.
- Victory is achieved by reducing the opponent’s health to zero.

## How to Play & Controls
1. Launch the game to enter the duel arena.
2. Use keyboard controls to select spells and plan your strategy.
3. Monitor your health and mana bars to outlast your opponent.
4. The first player to deplete their opponent’s health wins the duel.

### Keybinds:
- `F` – Cast Fireball
- `W` – Cast Water Orb
- `P` – Cast Poison
- `R` – Use Recovery
- `S` – Activate Sleep
- `I` – Open Info Menu
