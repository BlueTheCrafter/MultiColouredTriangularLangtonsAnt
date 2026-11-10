# Multi-Coloured Triangular Langton's Ant:
The Langton's Ant is a two dimensional Turing Machine that creates a grid pattern. An Ant, starting at the enter, usually moves around the grid changing the colour of the grid as it does so. This is determined by certain rules. For the original Langton's Ant, these are the rules:
* If a white tile is encountered, turn 90 degrees clockwise, change the current tile to black, and move one step forward.
* If a black tile is encountered, turn 90 degrees anti-clockwise, change the current tile to white, and move on step forward.

## Variation of the Langton's Ant:
**Multi-Colour**:These are also well researched, it includes including a third or fourth colours for the Langton's Ant, this could also include non-determinism by including more colours than four. 

**Triangular Grid**: These are moderately researched, with each grid being in the shape of a triangle, allowing only three different directions that can be taken.

There are multiple other variations including the use of third dimensional Langton's Ant, using different grids, having multiple Ants and much more.

## Project:
This project will be combining both the multi-colour and triangular grid. The Langton's Ant will start by facing the top most point in the triangular cell that it spawns in. It will then turn based on the colour of the current grid. Whichever edge it faces after the turn, it will then move to its adjacent cell. Below is an image of the Ant's starting configuration:

<img width="375" height="385" alt="image" src="https://github.com/user-attachments/assets/6a2a5663-95b3-40fd-b644-50f0b8a934dc" />

This create a Langton's Ant that behaves the following on a triangular grid:
* If a grey tile is encountered, it will rotate 60 degrees clockwise, changing the tile to black, and move one step forward.
* If a black tile is encountered, it will rotate 60 degrees anti-clockwise, changing the tile to white, and move one step forward.
* If a white tile is encountered, it will rotate 180 degrees, changing the tile to grey, and move one step forward.

The following are the first ten steps of this machine if it were run on a completely blank grid:
<img width="1077" height="717" alt="image" src="https://github.com/user-attachments/assets/67ce9402-8599-4d3b-8499-64d3bc2b5332" />
(The black arrows show the transition between steps, and the red arrows on the top right hand corner of each step show the direction of the ant. The tile with the red outline is the tile currently with the Ant.)
