# 🚀 LunarLander Deep Q-Learning Agent

A reinforcement learning project that implements a **Deep Q-Network (DQN)** to train an agent to solve the **LunarLander-v3** environment.  
The project focuses on understanding and implementing core DQN concepts rather than model racing or hyperparameter optimization.

---

## 🔍 Overview

This project demonstrates how an agent can learn optimal behavior through interaction with an environment using **Deep Reinforcement Learning**.

Instead of relying on tabular Q-learning, the agent uses a neural network to approximate Q-values, enabling learning in a **continuous state space**.

**Key goals of the project:**
- Understand how Deep Q-Learning works end-to-end  
- Implement experience replay and target networks for stable training  
- Observe how exploration–exploitation trade-offs affect learning  

---

## 🧠 Core Concepts Implemented

- Deep Q-Learning (DQN)  
- Experience Replay  
- Target Networks with Soft Updates  
- ε-greedy Exploration Strategy  
- Batch-based Learning with PyTorch  
- Reward-based Convergence Monitoring  

These techniques are essential for stabilizing learning in deep reinforcement learning environments.

---

## 🌍 Environment

- **Environment:** LunarLander-v3 (Gymnasium)  
- **State Space:**  
  8 continuous variables representing position, velocity, angle, and contact sensors  
- **Action Space:**  
  4 discrete actions controlling the lander’s thrusters  
- **Goal:**  
  Achieve a safe landing between the flags with minimal fuel usage  

---

## 🏗️ Architecture Overview

- **Q-Network:**  
  Fully connected neural network with two hidden layers  

- **Local Network:**  
  Learns from sampled experiences  

- **Target Network:**  
  Provides stable Q-value targets  

- **Replay Buffer:**  
  Stores and samples past experiences uniformly  

- **Optimizer:**  
  Adam  

- **Loss Function:**  
  Mean Squared Error (MSE)  

---

## 🛠️ Tech Stack

- Python  
- PyTorch  
- NumPy  
- Gymnasium  
- Google Colab  

---

## ▶️ Getting Started

### 1. Clone the repository
git clone https://github.com/harshinikailasam/lunarlander_dqn.git
cd lunarlander_dqn

### 2.	Install dependencies:
pip install -r requirements.txt

### 3. Run the notebook
notebooks/Deep_Q_Learning_for_Lunar_Landing.ipynb