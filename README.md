# Snake_Game

📌 Project Overview
This project implements the classic Snake Game using Reinforcement Learning, specifically the Q-Learning algorithm. The game environment is a simple grid, making it an ideal platform for understanding the state-action-reward cycle.
✨ Features
- Classic Snake Game implemented using Pygame.
- AI agent learns to play using Q-Learning.
- Real-time visualization of gameplay and learning progress.
- Self-generated dataset through gameplay.
- Adjustable training parameters for experimentation.
🛠️ Tech Stack
- Python
- Pygame – for game interface
- OpenAI Gym – for RL environment abstraction
- NumPy – for matrix operations
- Matplotlib – for training visualization (optional)
📂 Dataset
The dataset is self-generated through gameplay. The agent explores different game states, records its actions, and stores the resulting rewards. This dataset grows over time as the Q-table updates, improving the agent's performance.
🚀 Installation & Setup
1. Clone the repository:
```bash
git clone <repo-url>
cd snake-rl
```
2. Install dependencies:
```bash
pip install pygame gym numpy matplotlib
```
3. Run the training script:
```bash
python train.py
```
4. Run the game with AI:
```bash
python play.py
```
📖 How It Works
1. **Game Environment** – Snake moves in a grid environment implemented with Pygame.
2. **State Representation** – Game state is represented by snake position, direction, and food location.
3. **Q-Learning Algorithm** – Agent updates its Q-table based on actions taken and rewards received.
4. **Reward Function** – Positive reward for eating food, negative reward for dying.
5. **Exploration vs. Exploitation** – Agent balances between trying new moves and using learned strategies.
🎯 Learning Outcomes
- Understanding the Q-Learning algorithm.
- Designing a reward function to guide learning.

Snake Game Q-Learning Training Progress - Moving Average Scores:
<img width="997" height="547" alt="Snake Game Q-Learning Training Progress - Moving Average Scores" src="https://github.com/user-attachments/assets/730ddebc-7db4-4124-91f8-f88e01fb7000" />

- Implementing reinforcement learning in a game environment.
- Integrating Pygame with OpenAI Gym for custom environments.
