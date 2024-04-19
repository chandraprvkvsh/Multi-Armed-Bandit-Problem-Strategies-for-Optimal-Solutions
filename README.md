# Brief Introduction

Objective of this project was to illlustrate various ways of approaching a multi armed bandit problem

# Details of the project

In '1_Epsilon_Greedy_Selection' we examine the trade - off between Exploration and Exploitation. To have a better control, we use a custom implementation of a Multi Armed Bandit that acts similar to Gym environments.
Given below is a Multi - Armed Bandit environment with Bernoulli distribution.

In '2_UCB_Adv_Selection' we simulate a practical application of Multi-Armed Bandits. There are 10 different advertisements, that were repeated for 10,000 rotations. The Agent has to select one advertisement amongst 10 for placement. The dataset describes whether the picked advertisement would be clicked (1) or not (0). Let us compare Epsilon Greedy and UCB methods for this problem.

In '3_Random_Selection' we use random selection procedure for the bandit problem and proceed further.
