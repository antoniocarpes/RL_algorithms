# RL Algorithms

This repository contains implementations of various Reinforcement Learning (RL) algorithms and dynamic programming methods.

## Notebooks

1. **First Notebook**: Implements standard RL algorithms and dynamic programming methods such as **Value Iteration** and **Policy Iteration** for optimal policy search.
   
2. **Second Notebook**: Implements **TD(0)** and **LSTD** (Least Squares Temporal Difference) to study the performance of simple policies. Using the LSTD implementation, it also builds an approximate **Policy Iteration** method that incorporates LSTD as a subroutine.

3. **Third Notebook**: Builds on the LSTD implementation from the second notebook to develop a **Soft Policy Iteration** method. The algorithm iteratively performs two steps in each iteration: policy evaluation using LSTD, followed by a **Q-function** estimate for policy improvement.


