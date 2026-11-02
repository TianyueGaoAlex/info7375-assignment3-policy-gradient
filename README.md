# INFO 7375 — Assignment 3: Policy Gradients

PyTorch implementations of the three policy-gradient algorithms from Sutton & Barto, Chapter 13:

- REINFORCE
- REINFORCE with baseline
- One-step Actor-Critic

Each algorithm is evaluated on five Gymnasium environments: CartPole-v1, Acrobot-v1, LunarLander-v3, FrozenLake-v1 and Blackjack-v1. There are 5 runs per environment, and each environment has a chart in the style of S&B Figure 13.2.

**Open [`policy_gradient.ipynb`](policy_gradient.ipynb).** It is a single, self-contained notebook with all code, training logs, plots and discussion.

Modal Notebooks has been shut down, so the notebook was run in Jupyter, and all 75 training runs were executed on [Modal](https://modal.com) through the `modal` Python library (see Section 6).
