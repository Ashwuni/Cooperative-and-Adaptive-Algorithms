# Cooperative-and-Adaptive-Algorithms

Assume a 25 × 25 two-dimensional maze. Each square in the maze has an (x,y) coordinate, with the bottom-left corner
being (0,0) and the top-right corner being (24,24). Each position in the maze can be either empty or blocked. In
addition, there are two “special” positions, the starting position and the exit position.
The agent can only move up, down, left or right, but never diagonally. It also cannot enter blocked positions or move
outside the maze. Its objective is to find a path from its starting position to the exit position, preferably the cheapest
one. The cost of a path is the number of positions the agent has to move through, including the starting and exit
position. The map of the maze is given in the figure below.
Requirements
      • Implement a code to find a path from the starting position to the exit position using (1) Breath-First Search,
      (2) Depth-First Search, and (3) A* Search. For the A* Search, you must define an appropriate heuristic
      function, and justify your choice. Your implementation should output information about the search, including
      the complete path, its cost, and the number of nodes explored (or squares checked) before finding it.
      Deliverables
      Your answer should include the following:
          1. Upload the code separately as a zip file and name it “YOUR NAME_Maze source code”.
          2. In the PDF that you submit for this assignment, for this question provide:
          a. A short description of your implementations of the search methods. In particular, for the A* Search,
          explain and justify your chosen heuristic function.
          b. Sample output of each search method you implemented on the maze of Figure 1.
          c. You will have to test each search technique three times:
                c.1. With the agent starting at S and ending at E1
                c.2 With the agent starting at S and ending at E2
                c.3 With the agent starting at (0,0) and ending (24,24)
