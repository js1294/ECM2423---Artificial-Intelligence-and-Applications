# ECM2423-Artificial-Intelligence-and-Applications
Developer
-----------
Jack Shaw- https://github.com/js1294

Description
-----------
The coursework is split up into two different questions: one was to create an A* algorithm to solve the 8-puzzle problem, and two to create an evolutionary algorithm to solve a sudoku problem.

The A* algorithm uses two different heuristics - euclidean distance and manhattan distance. It also has a general-purpose version that works for all possible start and end grids using manhattan distance as the heuristic since it is the best heuristic.

The evolutionary algorithm works using this pseudocode:

    1. Initialise the population by replacing blank spaces with random numbers (1-9)
    2. Evalutate the fittness of each grid
    3. Repeat until fittest cadidate is found or at maximum number of generations
    4.     Select the fittest to be parents
    5.     Recombine the pairs of parents
    6.     Mutate the offspring of the parents
    7.     Evalutate the fittness of each new grid

Requirements
-----------
This is written in python on a Jupyter notepad. 

Running the Project
-----------
Junyter can be installed at https://jupyter.org/install or be run online using https://colab.research.google.com/. Each code can be run separately and can take a while to produce results.

For the general-purpose A* algorithm, you will need to enter a start and end grid in the format: 1 4 2 3 5 6 7 8 0. The zero is used to represent the blank tile. Each grid must have the numbers 0 to 8, and both grids must have the same parity; otherwise, they are unsolvable.

For the evolutionary algorithm, it shall run experiments on three different sudoku grids with the population sizes 10, 100, 1000 and 10000. Each experiment is run five times to find the averages. This is 60 different runs, so it will take a considerable amount of time to run all of them. 
