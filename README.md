# Q-learning-RL

In this work, I designed a 5×6 maze as required. Initially, I attempted to create a more complex maze to make the task more challenging. However, the training process took significantly longer, so I decided to proceed with a smaller maze size.

For the reward system, I introduced a negative reward whenever the agent collided with a wall and assigned a reward of 10 for reaching the goal. Additionally, I penalized every step the agent took to encourage it to find the most optimized path. However, this approach increased the training time.

Looking at the graph of steps per episode, we can observe that in the early episodes, the number of steps required to reach the goal fluctuates significantly, with some episodes requiring over 300 steps. This suggests that the agent was still exploring and learning an efficient policy. Around episode 15, the steps drastically decrease, indicating that the agent has successfully learned to navigate the maze more efficiently. Beyond this point, the number of steps remains relatively low with only minor fluctuations, showing that the agent has converged to an optimal or near-optimal policy.
