# DQN Recommender System 🚀🤖  
### A Deep Q-Learning Approach to Personalized Recommendations 🎯  

Welcome to the **DQN Recommender System**, a project that harnesses the power of Deep Q-Learning to deliver personalized item recommendations! Built using a Deep Q-Network (DQN), this system is trained on the Amazon review dataset to suggest items with impressive accuracy and coverage. Whether you're a researcher, developer, or enthusiast, I'am excited to share this journey with you! 🎉  

---

## 🌟 Overview  
This project implements a reinforcement learning-based recommender system that learns to optimize recommendations through trial and error. The DQN model explores user preferences, exploits learned patterns, and achieves strong performance on unseen data. After 2000 training episodes, it’s ready to shine in testing, boasting:  
- **🎯 Precision@5**: 0.7504 – 75% of top 5 picks are relevant  
- **📈 Recall@10**: 1.0000 – Full coverage of relevant items in top 10  
- **🏆 Average Reward**: 31.8 out of 50 – A solid win!  

---

## ⚙️ How It Works  
The system operates within a custom Gym environment tailored to the Amazon dataset:  
1. **🛠️ Training**: 5000 episodes, peaking at a reward of 33.6 with `epsilon=0.0820`.  
2. **📊 Testing**: Evaluated over 250 episodes, averaging 31.8 reward in full exploitation mode (`epsilon=0.0`).  
3. **🔑 Key Parameters**:  
   - History length: `N=5`  
   - Episode steps: `M=10`  
   - Exploitation tweak: 75% chance of recommending known items  

Built with PyTorch, Pandas, and NumPy, it’s a robust blend of RL and deep learning techniques. 🧠  

---

## ✨ Features  
- **🔥 High Accuracy**: Outperforms random and popularity baselines significantly.  
- **👥 User-Centric**: Leverages user history and Q-values for tailored suggestions.  
- **💾 Pre-Trained**: Includes a saved model (`dqn_model.pth`) for quick testing.  
- **🔍 Transparent**: Detailed logs to track recommendation decisions.  

---

## 🚀 Getting Started  

### 📌 Prerequisites  
- 🐍 Python 3.8+  
- 🔥 PyTorch  
- 🗂 Pandas  
- 🔢 NumPy  
- 🎮 Gym  

### 🛠 Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/dqn-recommender-system.git
   cd dqn-recommender-system
   ```  

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
---

## 📊 Results  
The model performs significantly better than traditional recommendation baselines. Evaluation metrics indicate that Deep Q-Learning is an effective approach for personalized recommendations. Below are some key results:  

| 📌 Metric       | 📊 Value  |
|-------------|--------|
| 🎯 Precision@5 | 0.7504 |
| 📈 Recall@10   | 1.0000 |
| 🏆 Avg Reward  | 31.8   |

---

## 🔮 Future Improvements  
- **⚡ Hyperparameter tuning** for further optimization.  
- **🛍️ Integration with real-world applications** like e-commerce platforms.  
- **🧠 Exploring alternative deep RL methods** such as PPO and A2C.  

---

## 🤝 Contributing  
Contributions are welcome! Feel free to fork this repository and submit a pull request with enhancements or fixes. 🙌  

---

## 📜 License  
This project is licensed under the MIT License

---

## 📬 Contact  
For any questions or collaborations, reach out via GitHub issues or email at pandeankitr@gmail.com

Happy coding! 🚀🎉

