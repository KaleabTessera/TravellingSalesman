# TravellingSalesman
The TSP (Travelling Salesman Problem) is an optimization problem, where a salesman or agent, want to visit **n** distinct cities (represented as vertices), while choosing the shortest **distance travelled/cost** (represented by edges). The problem can be rephrased as finding a **Hamiltonian circuit within minimun cost/length**. 

In this implementation, we use the 2-opt Heuristic approach on a Symmetric Travelling Salesman Problem , where we began with an initial T and replace 2 edges in tour, with 2 other edges in tour, until we gradually find a Tour with smaller length/cost. 
