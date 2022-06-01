N-Queen

In this section, you will develop a solver for the n-queens problem, wherein n queens are to be placed on an n × n chessboard so that no pair of queens can attack each
other. Recall that in chess, a queen can attack any piece that lies in the same row, column, or diagonal as itself. A sensible representation for a board configuration
is a list of numbers between 0 and n−1, where the ith number designates the column of the queen in row i for 0 < i ≤ n. A complete configuration is then specified by
list containing n numbers, and a partial configuration is specified by a list containing fewer than n numbers.


Lights Out

The Lights Out puzzle consists of an m × n grid of lights, each of which has two states: on and off. The goal of the puzzle is to turn all the lights off, with the
caveat that whenever a light is toggled, its neighbors above, below, to the left, and to the right will be toggled as well. If a light along the edge of the board is
toggled, then fewer than four other lights will be affected, as the missing neighbors will be ignored.In this section, you will investigate the behavior of Lights Out
puzzles of varioussizes by implementing a LightsOutPuzzle class.

Linear Disk Movement

In this section, you will investigate the movement of disks on a linear grid. The starting configuration of this puzzle is a row of ` cells, with disks located on cells
0 through n − 1. The goal is to move the disks to the end of the row using a constrained set of actions. At each step, a disk can only be moved to an adjacent empty
cell, or to an empty cell two spaces away if another disk is located on the intervening square. Given these restrictions, it can be seen that in many cases, no movements
will be possible for the majority of the disks. For example, from the starting position, the only two options are to move the last disk from cell n − 1 to cell n, or to
move the second-to-last disk from cell n − 2 to cell n.
