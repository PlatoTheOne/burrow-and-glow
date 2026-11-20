# Burrow & Glow

A playable first level for a two-player browser puzzle game. A mole and a firefly must work together to escape a flooding burrow.

Download [burrow-and-glow.html](https://raw.githubusercontent.com/PlatoTheOne/burrow-and-glow/main/burrow-and-glow.html) and open it in Chrome. Both players share one keyboard. No installation or server is required.

| Character | Move | Action |
| --- | --- | --- |
| Mole | W, A, S, D | F to dig |
| Firefly | Arrow keys | / to flash |

Fly to the glowing flower on the right side of the glass and flash to reveal the drain. The mole can open it by digging from an adjacent tile. Once the water recedes, bring both characters to the exit in the bottom-right corner.

The single HTML file contains the Canvas renderer, keyboard controls, tile map, and level state. The first planned Devin task is to extract the level rules into a deterministic module and add regression tests for the drain, flooded passage, and two-player exit.
