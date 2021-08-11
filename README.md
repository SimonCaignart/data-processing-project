# CESI - Data Processing Project

The goal of this shcool project was to create a metaheuristic algorithm that could solve the traveling salesman problem, using Python and Jupyter.

## Context

This project was a response to the ADEME call. This company needed an algorithm that could solve the travelling salesman problem (TSP). The TSP asks the following question: "Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city exactly once and returns to the origin city?". It is an NP-hard problem in combinatorial optimization, important in theoretical computer science and operations research.

## Our solution

To solve this problem, we used two algorithms. Firstly, we used the nearest neighbor greedy algorithm. This one will provide our second algorithm with a solution that is closer to the optimal, resulting in less useless iterations. Our second algorithm is the Tabu Search algorithm. It's a metaheuristic that can get out of local optimums to search for a global optimum by degrading its current solution.


Nearest Neighbor -> Generate a first solution close to the optimum -> Tabu search algorithm with the previously generated solution for the initial solution -> Generate a solution even closer to the global optimum
