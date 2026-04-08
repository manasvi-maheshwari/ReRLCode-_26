# 🧠 Synapse — AI-Powered Study Planner

Synapse is an intelligent, personalized study planner that uses **Reinforcement Learning (Q-Learning)** to generate optimized study roadmaps based on your strengths and weaknesses.

It combines AI decision-making with a clean GUI to help you focus on what matters most.

---

## 🚀 Features

- 🎯 Personalized Study Plan based on your current skill levels  
- 🧠 AI-Powered Scheduling using Q-learning  
- 📊 Adaptive Learning – improves recommendations over time  
- 🔄 Balanced Subject Distribution (avoids repetition & burnout)  
- 💡 Actionable Tasks for each subject (Beginner → Advanced)  
- 🖥️ Modern GUI built with Tkinter  

---

## 🗂️ Project Structure

.
├── app.py
├── brain.py
├── logic.py
└── q_table.json

---

## ⚙️ How It Works

1. Input your confidence levels for each subject (0–100%)
2. The AI identifies weak areas
3. Generates a study sequence using reinforcement learning
4. Displays a roadmap with actionable tasks

---

## 🧠 AI Approach

- Uses Q-Learning
- State: (time_slot, weakest_subject)
- Action: next subject to study
- Reward system encourages improvement and balance

---

## 🖥️ Installation & Setup

### Clone the repository
git clone https://github.com/manasvi-maheshwari/synapse-study-planner.git

### Install dependencies
pip install numpy

### Run the application
python app.py

---

## 🔮 Future Improvements

- Data visualization
- Web & mobile versions
- Cloud sync
- More customization

---

## 📄 License

MIT License
