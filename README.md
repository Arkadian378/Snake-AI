# 🐍 Snake AI with Reinforcement Learning

An implementation of the classic **Snake** game where an agent learns to play autonomously using **Reinforcement Learning** techniques.

## 🚀 Overview

This project demonstrates how an agent can learn optimal strategies through interaction with the environment, progressively improving its performance without being explicitly programmed.

The agent’s goal is to maximize the score by eating as much food as possible while avoiding collisions.

---

## 🧠 Technologies Used

- Python 🐍  
- NumPy  
- PyGame (for simulation)  
- PyTorch  
- Reinforcement Learning (Deep Q-Learning)

---

## ⚙️ How It Works

The agent uses a neural network to approximate the Q-function:

- **State**: representation of the environment (snake position, food location, direction, dangers)
- **Actions**: [left, right, straight]
- **Reward**:
  - +1 → eats food 🍎  
  - -1 → collision 💀  
  - 0 → normal movement  

### Algorithm

- Deep Q-Network (DQN)  
- Experience Replay  
- Epsilon-Greedy Strategy (exploration vs exploitation)  

---

## 🔧 Possible Improvements

- Double DQN  
- Dueling Networks  
- Prioritized Experience Replay  
- Hyperparameter tuning  
- Advanced reward shaping  

---

## 📚 Key Concepts

- Reinforcement Learning  
- Markov Decision Process (MDP)  
- Q-Learning  
- Deep Neural Networks  

---

## 🤝 Contributing

Pull requests and suggestions are welcome!
