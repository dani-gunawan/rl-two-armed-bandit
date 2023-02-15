# rl-two-armed-bandit
A reinforcement learning project to demonstrate a two-armed bandit agent maximizes its total reward. The reward distribution for the first lever is Gaussian and the second lever is Binomial Gaussian. However, in this problem, we assume the reward distributions are unknown. The agent only sees a realization of a reward after selecting an action. 

The goal of this project is to understand the concept of exploration and exploitation. Pure exploitation will limit the chance that a good action is selected and not guarantee that the selected action is the best. Because the agent with e-greedy policy = 0 will never test other actions to confirm if the current one is the best or not. Therefore, the agent will miss the actions that could provide a higher long-term return.
