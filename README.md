This code implements a self-adaptive optimization algorithm using simulated annealing with a restart strategy to solve a defined cost function. 
Inspired by the lectures and course materials presented in the Computational Intelligence course (01URROV), it initializes a current solution and iteratively tweaks it while accepting new solutions based on their costs and a decreasing temperature. 
The algorithm adapts the intensity of changes based on recent improvements, allowing for aggressive tweaks when progress is made and moderating them when it stalls. 
It also monitors valid costs to terminate early if consecutive iterations yield the same result, improving efficiency. 
The best solution found across all restarts is tracked, and the cost progression is visualized, while progress bars enhance user experience by indicating the remaining iterations and restarts.
The number of maximum iterations and restarts can be adjusted according to the number of sets and universe size.

Results
Instance --- Cost
1   --  274.8
2   -- 6337.6
3   -- 128578.2
4   -- 21028680.8
5   -- 4900785.7
6   -- 5383520.1
