
---

## 📌 **VizdoomXppo/README.md**  

```markdown
# ViZDoom AI Agent 🎮🤖  

A **Deep Q-Learning (DQN)** and **PPO-based agent** trained in the **ViZDoom environment** to play Doom with high accuracy and survival time.  

## 🚀 Features  
- **Deep Q-Learning Agent:** Learns directly from raw pixel inputs.  
- **PPO Integration:** Stable and efficient reinforcement learning training.  
- **Evaluation Metrics:** Survival time, hit rate, and latency.  
- **Performance:** Achieved **+86.4 reward** and **93.5% accuracy** after 10k steps.  

## 🛠 Tech Stack  
- **Python**, **NumPy**, **Pandas**  
- **PyTorch** (neural networks)  
- **ViZDoom** (Doom environment)  
- **Stable Baselines3** (RL algorithms)  

## 📊 Results  
- **Cumulative Reward:** +86.4  
- **Accuracy:** 93.5% after 10k steps  
- **Improved Survival Time** in combat scenarios  

## 📂 Repository Structure  
├── configs/ # ViZDoom configs
├── models/ # Trained agents
├── notebooks/ # Training experiments
├── src/ # Core code
│ ├── dqn_agent.py # Deep Q-Learning agent
│ ├── ppo_agent.py # PPO agent
│ ├── train.py # Training script
│ └── evaluate.py # Evaluation pipeline
└── README.md

## ▶️ Usage  
```bash
# Clone repo
git clone https://github.com/Syntaxforall/VizdoomXppo.git
cd VizdoomXppo

# Install dependencies
pip install -r requirements.txt

# Run training
python src/train.py
