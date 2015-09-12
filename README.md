# Random-Walk

The Tasks
1. Write a class called RandomWalk. RandomWalk is to have a two-dimensional array as an
instance variable. The two dimensional array is to represent the number of times each tile of
the n × m rectangular array of tiles in the room is visited.
2. Write a constructor that takes two arguments representing the the dimensions of the room
(in tiles). Write a default constructor that takes no arguments and initializes the size of the
room to some default dimensions. Initialize the 2D-array appropriately.
3. Write a public method called runBug that takes no parameters and runs the simulation.
4. Write a (private) method that generates the next move for the bug. The method is to pick
one of the eight adjacent tiles randomly. (See Section 2 below and Section 3.4 in the text.)
5. Write a public method called getTotalSteps that takes no arguments and returns the total
number of steps taken by the bug during the simulation.
6. Write a public method called printRoom that prints out the 2D tile array on the console
(terminal) in a nicely formatted fashion.
7. Write a main method that creates several instances of the RandomWalk, calls runBug for
each instance and prints the total number of steps taken and the contents of the 2D tile array
in each case.
