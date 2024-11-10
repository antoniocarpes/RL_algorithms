#RL algorithms

The first notebook in this repo contains implementations for standard RL algorithms and dynamic programming methods such as Value and Policy Iteration for optimal policy search.

The second notebook contains implementations of TD(0) and LSTD to study the performance of simple policies. Then, by uisng the LSTD implementation, it builds an approximate policy iteration method (that contains LSTD as a subroutine).

The third notebook uses again the LSTD implemented in the second notebook to implement a soft policy iteration method. The algorithm is iterative with a double step: in each iteration a policy evaluation with LSTD is performed and then a Q-function estimate allows for policy improvement.
