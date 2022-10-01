# Conway's Game of Life

I simulated the Conway’s game of life implementing classes like Cell, Landscape, LandscapeDisplay, and LifeSimulation. 
One particular location in a grid was represented using Cell object. 
We used a two dimensional grid of cells to create a landscape. 

The Landscape class has a method called getNeighbors() that returns the neighbors of a cell. 
The updateState() method in the Cell class checked the number of alive neighbors of a particular cell and updated the state of the cell either as alive or dead according to the rules of the game. 
The games rules says that the a live cell will live to the next generation only if there are no less than 2 or no more than 3 alive neighboring cells. 
If the cell is dead, the only way it could be alive is if there are exactly 3 alive neighboring cells. 
There is interaction between the classes and the different variables and methods has been assigned differently according to their accessibility (private / public). 
This project helps to understand the concept of 2 dimensional array, object oriented programming, constructor, field, variables, for loops, static and non-static methods.
