# Binary-Maze-Solver

solve_dfs takes a binary maze and returns a path if there is an existing path, if not return null. 
possible_moves takes maze and the current position together with height and width of the maze and returns the possible allowed movements.

For example, the solve_dfs function will take maze parameter as:

maze = [[0,0,0,0,0,0],
        [0,1,0,0,0,0],
        [0,0,1,1,1,0],
        [0,0,0,0,0,0],
        [1,0,0,0,1,0]]   

The returned path will be:

path => [(0, 0), (0, 1), (0, 2), (0, 3), (0, 4), (0, 5), (1, 5), (2, 5), (3, 5), (4, 5)]
