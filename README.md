# Blockrush
<img src="https://cdn.discordapp.com/attachments/404884236542410753/528219427452354560/6C9D2F44-F707-480C-AF45-DE76D772FCE8.jpeg" style="position:absolute; top:10%; right:10%; transform: translateX(-100%) translateY(-50%);"
Blockrush is a simple Puzzle game created in Lua, using Pico 8. We made the first version in two days for the Pixeler's game jam. Because we liked the concept, we decided to continue it's development.
The concept is simple : you play as a cube in a 2D world. When you move, you cannot stop until you reach a solid object. To finish a level, get to the treasure chest ! There are also hidden crowns that you can (you don’t have to) pickup during your play.

Controls :

Menu :

- Left and right arrow to navigate
- X, V, or M to select a level
- C, Z, or N to toggle music


In game :

- Move with arrow keys
- X, V, or M to reset the level, or to teleport if on a teleporter
- C, Z, or N to go back to the menu


Objects :

- Treasure chest : pick it up to finish the level
- Crown : an optional collectible that can be picked up in each level, picking it up brings you to the start of the level.
- Orb : stops you on your track and allows you to change direction.
- Teleporter : teleports you to the teleporter of the corresponding color when X, V, or M is pressed.
- Wall teleporter : teleports you to the corresponding teleporter on the same line when moving towards it. Your direction remains the same.
- Electricity : kills you whenever you touch it.
- Wall spikes : kills you if you move towards them.
- Arrow : changes your direction to the arrow's direction.
