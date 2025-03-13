# 🦖 Dino AI - NEAT Neural Network 🤖

## 📌 Description
Dino AI is a reinforcement learning project that utilizes the NEAT (NeuroEvolution of Augmenting Topologies) algorithm to train an artificial intelligence to play the Google Chrome Dino game. The AI learns to jump over obstacles and maximize its score over multiple generations through evolutionary strategies.

## 🎯 Objective
The main goal of this project is to experiment with NEAT to evolve a neural network that can effectively play the Dino game by learning from previous generations and improving its decision-making process.

## ⚡ Features
- 🧠 Uses the NEAT algorithm to evolve an AI player.
- 🎮 Implements reinforcement learning by rewarding survival and penalizing collisions.
- 📊 Displays real-time AI progress, game speed, and best score.
- 🚀 Adjusts the game speed dynamically as the AI improves.

## 🛠 Installation
### ✅ Prerequisites
- 🐍 Python 3.10+
- 🎮 Pygame
- 🧬 NEAT-Python

### 📥 Steps
1. Clone this repository:
   ```sh
   git clone https://github.com/luisalejandrojaramillo/Dino-game-IA
   cd Dino-game-IA
   ```
2. Install dependencies:
   ```sh
   pip install pygame
   pip install neat-python
   ```
3. Run the program:
   ```sh
   python main.py
   ```

## 🏗 How It Works
1. The AI receives four inputs:
   - 📍 Dinosaur's Y position
   - 📏 Distance to the next obstacle
   - ⚡ Game speed
   - ⛰ Obstacle height
2. The neural network decides whether the dinosaur should jump based on the processed inputs.
3. 🏆 The fitness function rewards survival time and penalizes collisions.
4. 🔄 Over multiple generations, the AI improves its decision-making through natural selection.

## ⚙ Configuration
The `config.txt` file defines the NEAT settings, such as mutation rates, population size, and fitness criteria. You can modify these parameters to experiment with different learning behaviors.

## 🚀 Future Improvements
- 🌵 Implement different types of obstacles.
- 👀 Improve visualization for better debugging.
- 🔧 Fine-tune NEAT hyperparameters for better performance.

## 📜 License
This project is open-source and available under the MIT License.

## Author
[Luis Alejandro Jaramillo](https://github.com/luisalejandrojaramillo)
