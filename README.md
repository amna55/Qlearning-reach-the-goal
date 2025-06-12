# Qlearning-reach-the-goal

Q-learning is a model-free RL algorithm used to find an optimal action-selection policy for finite Markov Decision Processes (MDPs).

This means that the agent does not need an understanding of the environment (model-free) to learn and act, and keeps track of the optimal actions to take in given states that it observes- best used in environments with a finite set of steps, states, and actions to take (finite MDP). Q in this case stands for "Quality"

Core Concepts
Value-based learning: Q-learning estimates the value of taking actions in states to inform decision-making.

Exploration vs. Exploitation: The agent must balance trying new actions (exploration) with using known good actions (exploitation).

State-action pairs: Instead of learning values for states alone, Q-learning considers the value of specific actions in each state.

Iterative improvement: Q-values are continuously updated based on new experiences, gradually improving the policy.

In rech the goal our agent has to reach the goal of this 3x3 Grid. The end goal will be to create a Q-Table that stores all of the Q-Values learned through the RL training.

Q-value: Represents the expected utility of taking a specific action in a given state, this is the value kept that determines how 'useful' an action is given the current state.
Q-table: A lookup table storing Q-values for all state-action pairs, the main brains behind your agent at the end of training.

This will show, at each tile in our grid, what the best action is to take. A higher Q-Value for an action in a given state action pair represents the optimal learned action.


![image](https://github.com/user-attachments/assets/47e22dc2-55cd-4da9-8153-c6313f726d13)
