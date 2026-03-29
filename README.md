<div align="center">

# :joystick: Reinforcement Learning

### Teaching agents to learn from interaction -- from Q-learning to multi-agent systems

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![OpenAI Gym](https://img.shields.io/badge/OpenAI_Gym-0.26+-0081A5?style=for-the-badge&logo=openaigym&logoColor=white)](https://gymnasium.farama.org)
[![Stable-Baselines3](https://img.shields.io/badge/Stable--Baselines3-2.x-4B8BBE?style=for-the-badge&logo=python&logoColor=white)](https://stable-baselines3.readthedocs.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## Overview

This repository is a portfolio of reinforcement learning projects, progressing from foundational tabular methods to deep RL and multi-agent systems. Each project implements RL algorithms from scratch or uses established libraries, with clear explanations of the theory behind each approach.

The goal is to build a thorough understanding of how agents learn optimal behavior through trial-and-error interaction with environments.

## Topics Covered

| # | Topic | Algorithms / Techniques | Status |
|---|-------|------------------------|--------|
| 1 | **Multi-Armed Bandits** | Epsilon-greedy, UCB, Thompson Sampling | :hourglass: Planned |
| 2 | **Dynamic Programming** | Value Iteration, Policy Iteration | :hourglass: Planned |
| 3 | **Monte Carlo Methods** | First-visit MC, exploring starts | :hourglass: Planned |
| 4 | **Temporal Difference Learning** | TD(0), SARSA, Q-Learning | :hourglass: Planned |
| 5 | **Deep Q-Networks (DQN)** | DQN, Double DQN, Dueling DQN, PER | :hourglass: Planned |
| 6 | **Policy Gradient Methods** | REINFORCE, Advantage Actor-Critic (A2C) | :hourglass: Planned |
| 7 | **Proximal Policy Optimization (PPO)** | PPO-Clip, continuous & discrete action spaces | :hourglass: Planned |
| 8 | **Soft Actor-Critic (SAC)** | Off-policy, maximum entropy RL | :hourglass: Planned |
| 9 | **Model-Based RL** | World models, Dyna-Q, MuZero concepts | :hourglass: Planned |
| 10 | **Multi-Agent RL** | Independent learners, cooperative/competitive agents | :hourglass: Planned |
| 11 | **Reward Shaping & Curriculum** | Intrinsic motivation, curriculum learning | :hourglass: Planned |
| 12 | **RL for Real-World Problems** | Robotics, game playing, resource optimization | :hourglass: Planned |

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.10+ | Core language |
| Gymnasium (OpenAI Gym) | RL environments |
| Stable-Baselines3 | Pre-built RL algorithms |
| PyTorch | Neural network backends |
| NumPy | Numerical computing |
| Matplotlib | Training curve visualization |
| TensorBoard | Experiment tracking |
| Jupyter Notebook | Interactive development |

## Project Structure

```
Reinforcement_Learning/
|-- README.md
|-- bandits/                   # (planned) Multi-armed bandit experiments
|-- tabular_methods/           # (planned) DP, MC, TD learning
|-- deep_q_networks/           # (planned) DQN and variants
|-- policy_gradients/          # (planned) REINFORCE, A2C, PPO
|-- actor_critic/              # (planned) SAC, TD3 implementations
|-- model_based/               # (planned) World models, Dyna-Q
|-- multi_agent/               # (planned) Multi-agent RL projects
|-- environments/              # (planned) Custom environments
```

## Getting Started

### Prerequisites

```bash
pip install gymnasium stable-baselines3 torch numpy matplotlib tensorboard jupyter
```

### Running Notebooks

```bash
jupyter notebook
```

Navigate to the topic folder and open the corresponding `.ipynb` file.

## Roadmap

- [ ] Multi-armed bandit comparison (epsilon-greedy vs. UCB vs. Thompson)
- [ ] Q-Learning on FrozenLake / Taxi environments
- [ ] DQN for Atari game (CartPole, then Breakout)
- [ ] Policy gradient (REINFORCE) from scratch
- [ ] PPO with Stable-Baselines3 on continuous control
- [ ] SAC for MuJoCo locomotion tasks
- [ ] Multi-agent cooperative environment
- [ ] Custom environment design and training

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Part of the [DatariusAI](https://github.com/DatariusAI) organization**

</div>
