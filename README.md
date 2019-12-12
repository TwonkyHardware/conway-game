# conway-game
A Conway's Game of Life simulator in Python

Team: 2-4 people

Challenge: Intermediate

Conway's Game of Life (https://en.wikipedia.org/wiki/Conway's_Game_of_Life) is a simple 
cellular automaton program consisting of a grid of black and white pixels (or cells) that change
color based on the colors of surrounding pixels.

In broad terms, the program will consist of 
* A gridlike GUI for the user to specify the initial conditions
* An implementation of the following rules that determine when cells change color:
  1) A black cell adjacent to zero or one black cells becomes white
  2) A black cell adjacent to two or three black cells remains black
  3) A black cell adjacent to four or more black cells becomes white
  4) A white cell adjacent to exactly three black cells becomes black
* Logic to apply the above rules to all cells simultaneously, repeated over an indefinite 
sequence of time steps
* A gridlike display of pixels showing the game's result as an animation over time


