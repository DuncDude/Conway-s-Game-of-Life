# Conway-s-Game-of-Life
Conway's game of life visualized in python with pygame and rules displayed
THis is a visual repersentain of 
also known simply as Life, is a cellular automaton devised by the British mathematician John Horton Conway in
1970.[1] It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no 
further input. One interacts with the Game of Life by creating an initial configuration and observing how it 
evolves. It is Turing complete and can simulate a universal constructor or any other Turing machine. 
Made using python and Pygame. You will need to have the following Libraies downloaded to run this.
Random
Time
Os
Pygame

Once downloaded and in folder launch with the command

Sudo python gol5.py

The code will generate 200 random “live cells” in a 34 by 34 grid, the progam will then act as a Turing Complete 
following the rules to James COnway’s Game of Life which are as follows
Rules...

1. Any live cell with fewer than two live neighbours dies, as if by underpopulation.
2. Any live cell with two or three live neighbours lives on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overpopulation.
4.Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

The program will run until you close it or maximum recurrence has occured
