# Exercise

```python
Exercise: Travelling Salesman Problem
Allowed functions : malloc, free

Create a solution for the Travelling Salesman Problem (TSP). The TSP is as follows: A salesman wishes to visit each of n cities once and only once, starting from city 1, leaving and finally returning to city 1. To do this, the salesman wants to spend as little on travel costs as possible. She therefore needs to find the shortest route that allows her to visit all cities and return home.

Your task is to write a C program that, given a list of n cities and the distances between them, returns the shortest possible route that visits each city exactly once and returns to the original city.

Note: This problem is NP-hard. Please consider using concepts such as greedy algorithms, and dynamic programming to find an approximate solution.

Sample prototype could be:
void tsp(int **graph, int n); 

Where 'graph' is a 2D array such that graph[i][j] gives the distance between city 'i' and city 'j', and 'n' is the total number of cities. Your function should print the shortest route and its cost.

(The array is symmetric i.e., graph[i][j] = graph[j][i] and represents the full matrix)
```
# Submissions 
 git push your solution in this repo and hit /submit in Discord