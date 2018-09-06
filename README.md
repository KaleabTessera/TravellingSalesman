# TravellingSalesman
The TSP (Travelling Salesman Problem) is an optimization problem, where a salesman or agent, wants to visit **n** distinct cities (represented as vertices), while choosing the shortest **distance travelled/cost** (represented by edges). The problem can be rephrased as finding a **"Hamiltonian circuit with minimum cost/length"**. 

In this implementation, we use the 2-opt Heuristic approach on a Symmetric Travelling Salesman Problem, where we begin with an initial T and replace 2 edges with two new edges, with the aim to find a Tour with a smaller length/cost. This algorithm gradually improves and sets the current T to the **local minimum in it's Neighbourhood** (a set of two adjacent tours).
