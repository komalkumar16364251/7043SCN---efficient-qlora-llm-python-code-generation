# ChefHat Reinforcement Learning Agent using PPO

## Overview
This project implements a reinforcement learning agent using the Proximal Policy Optimization (PPO) algorithm to learn and play the ChefHat card game environment.

The agent interacts with the environment, learns from rewards, and improves its performance over time.

---

## Technologies Used

- Python 3.10
- Stable-Baselines3
- OpenAI Gym
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Algorithm Used

Proximal Policy Optimization (PPO)

PPO is a reinforcement learning algorithm that improves learning stability and efficiency using policy gradient methods.

---

### Instalation

You can use our pip installation:

```python
   pip install chefshatgym

```
Refer to our full [documentation](https://chefshatgym.readthedocs.io/en/latest/) for a complete usage and development guide.

## Environment

- ChefHat simulated card game
- 4-player environment
- Custom Gym-compatible wrapper

---

## Training Configuration

| Parameter | Value |
|---------|------|
| Algorithm | PPO |
| Timesteps | 20000 |
| Learning Rate | 0.0003 |
| Batch Size | 64 |
| Device | CPU |

---

## Performance Evaluation

The following evaluation metrics were generated:

- Learning Curve (Reward vs Steps)
- Average Reward per Episode
- Win Rate over Time
- Episode Length Analysis

These graphs show that the agent successfully learned and improved performance.

---

## Files Included

- chefhat_ppo_training.ipynb → Training code
- chefhat_ppo_model.zip → Trained model
- learning_curve.png → Reward vs Steps graph
- avg_reward.png → Average reward graph
- win_rate.png → Win rate graph
- episode_length.png → Episode length graph
- README.md → Project documentation

---

## Conclusion

The PPO reinforcement learning agent successfully learned from interaction with the ChefHat environment and improved its performance over time.

---

## Author

KOMAL KUMAR KARAMALA
16364251
Coventry University  
Task 2
