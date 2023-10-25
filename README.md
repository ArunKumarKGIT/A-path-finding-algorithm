# A-path-finding-algorithm

##What is A* Algorithm?

A* is a variant of Dijkstra's algorithm commonly used in games. A* assigns a weight to each open node equal to the weight of the edge to that node plus the approximate distance between that node and the finish. This approximate distance is found by the heuristic, and represents a minimum possible distance between that node and the end. This allows it to eliminate longer paths once an initial path is found. If there is a path of length x between the start and finish, and the minimum distance between a node and the finish is greater than x, that node need not be examined. 

##Why A* Algorithm is used?

    A* Search algorithm, unlike other traversal techniques, has “brains”. What it means is that it is really a smart algorithm which separates it from the other conventional algorithms. And it is also worth mentioning that many games and web-based maps use this algorithm to find the shortest path very efficiently (approximation). 
    
##ALGORITHM DESCRIPTION:
Consider a square grid having many obstacles and we are given a starting cell and a target cell. We want to reach the target cell from the starting cell as quickly as possible. 
What A* Search Algorithm does is that at each step it picks the node according to a value-‘f’ which is a parameter equal to the sum of two other parameters – ‘g’ and ‘h’. At each step it picks the node/cell having the lowest ‘f’, and process that node/cell.
g = the movement cost to move from the starting point to a given square on the grid, following the path generated to get there. 
h = the estimated movement cost to move from that given square on the grid to the final destination. This is often referred to as the heuristic, which is nothing but a kind of smart guess. We really don’t know the actual distance until we find the path, because all sorts of things can be in the way (walls, water, etc.). There can be many ways to calculate this ‘h’.

##MODULES IMPORTED:
	Pygame(For GUI)
	Math(For calculation of distance)
	Queue(priority queue)

##IMPLEMENTATION:
	Python
![need](https://github.com/ArunKumarKGIT/A-path-finding-algorithm/assets/77446060/275324d3-e5a1-47cd-b667-911e7de8d260)

![n1](https://github.com/ArunKumarKGIT/A-path-finding-algorithm/assets/77446060/d87dee6d-cae5-4b5e-a72a-0aa291ffe00b)

![n2](https://github.com/ArunKumarKGIT/A-path-finding-algorithm/assets/77446060/cf423d1b-b618-468b-ad81-0dc866dfa3d8)






