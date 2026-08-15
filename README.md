# 🐦 Flappy Bird — Deep Q-Network

This project implements a **Deep Q-Network (DQN)** agent that learns to play Flappy Bird using **Reinforcement Learning** and **PyTorch**.

The agent learns through trial and error by interacting with the environment and improving its action selection based on past experiences.

## 🎯 Learning Objective

The main objective of this project was to understand how **Deep Q-Networks extend traditional Q-Learning** by using a neural network to approximate Q-values.
This project builds upon the concepts learned through **SARSA and Q-Learning** and applies them to a more complex environment.

## 🧠 Concepts Implemented

- Deep Q-Network (DQN)
- Q-Learning
- Experience Replay
- Epsilon-Greedy Exploration
- Target Network
- Temporal Difference Learning

## 🎮 Environment

The project uses the **Flappy Bird Gymnasium** environment.

The agent learns to control the bird by selecting actions to avoid pipes and survive for as long as possible.

## 🤖 DQN Architecture

The neural network takes the current game state as input and predicts the Q-value for each available action.

```text
Game State
    ↓
Neural Network
    ↓
Q-Values
    ↓
Action Selection
    ↓
Environment
    ↓
Reward + Next State
```

## 🔄 Experience Replay

The agent stores its experiences in a replay memory:

```text
(state, action, reward, next_state, done)
```

Random batches of experiences are sampled during training to improve learning stability and reduce the correlation between consecutive experiences.

## 📂 Project Structure

```text
Flappy Bird/
├── Code/
│   ├── game_flappy_bird.py
│   ├── agent.py
│   ├── dqn.py
│   ├── experience_replay.py
│   └── parameters.yaml
├── Output/
│   └── flappy_bird.jpg
├── README.md
```

## 🛠️ Technologies Used

- Python
- PyTorch
- Gymnasium
- NumPy
- PyYAML

## 👩‍💻 Author

**Heer Shah**

Computer Science & AI/ML Student
