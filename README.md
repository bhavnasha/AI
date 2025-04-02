# AI
 Navigation with Multiple Goals
Navigation with Multiple Goals
Overview
This project demonstrates search algorithms to help a robot navigate a grid, collecting multiple goals before reaching an exit. Each goal may have different priorities or costs.

Features
BFS (Breadth-First Search): Finds the shortest path when all goals are unweighted.

A Search:* Finds the optimal path when goals have different weights or costs.

Comparative Analysis: Evaluates trade-offs between path length and goal priority.

Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/navigation-goals.git
cd navigation-goals
Run the script:

bash
Copy
Edit
python navigation.py
Modify maze, goals, and costs to test different scenarios.

Example Grid
nginx
Copy
Edit
S  .  .  #  .  G
#  #  .  #  .  #
.  .  .  .  .  .
.  #  #  #  .  E
S: Start position

G: Goal positions

E: Exit position

#: Obstacles

Algorithm Comparison
Algorithm	Path Found	Considerations
BFS	Finds shortest path in unweighted cases	Ignores goal priorities
A*	Finds optimal path with weights	Balances path cost and goal priority
Future Enhancements
Implement Dijkstra’s algorithm for a more generalized weighted search.

Allow diagonal movement.

Add visualization for better understanding.
