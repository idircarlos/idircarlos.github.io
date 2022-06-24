---
layout: post
title: Game of life
language: Python
---

**<a href="https://en.wikipedia.org/wiki/Sokoban" target="_blank">The game of Life</a>** is a cellular automaton designed by John Horton Conway in the 70's.
There are no players in this game, just an initial state. The game consists on a board with multpile cellules, which can be alive or dead. The initial state determines which cells are alive and dead.

There are only 3 rules in this game:

1. Any live cell with two or three live neighbours survives.
2. Any dead cell with three live neighbours becomes a live cell.
3. All other live cells die in the next generation. Similarly, all other dead cells stay dead.

Only with this 3 rules we can observe a lot of interesting patterns.

### Examples

Here is an infinite loop which generetes a lot of 'spacecraft'

<img src="../img/life/loop.mp4"
     alt="Loop"
     style="float: left; margin-right: 10px;" />