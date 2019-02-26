# nsga_sort
Ranks a set of objective values based Pareto dominance and crowding distance

The interesting part about NSGA-II i not the GA but the non-dominated sorting with crowding distance. Which boils down to a ranking of the population. This function returns only this ranking, to be used in NSGA-II or any other multiobjective algorithm.
