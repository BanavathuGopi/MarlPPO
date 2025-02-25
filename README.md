# MarlPPO
Multi-Agent Autonomous Drone Surveillance Using Deep Reinforcement Learning (MARLPPO)

🚀 MARLPPO: An Advanced Multi-Agent Deep Reinforcement Learning Framework for Drone Surveillance

📌 Overview

This repository presents MARLPPO, a multi-agent reinforcement learning framework for optimizing autonomous drone surveillance in urban environments. Built using Unity ML-Agents and Proximal Policy Optimization (PPO), MARLPPO enhances multi-drone coordination, reduces redundant coverage, and improves efficiency compared to traditional surveillance methods. This setup currently works for 3 drones, it also works for more no. of drones but changes need to be made in config.yaml tp include remaining drones and also in unity.

🌟 Key Features

✅ Multi-Agent Reinforcement Learning (MARL): Enables drones to collaborate and cover large areas efficiently.

✅ Proximal Policy Optimization (PPO): Enhances policy updates for stability and faster convergence.

✅ 3D Unity Simulation: Simulates real-world urban environments for training and testing.

✅ Optimized Surveillance Time: Reduces surveillance time by up to 40% compared to traditional models.

✅ Improved Area Coverage: Achieves 25% more area coverage with multiple drones.

✅ Obstacle Avoidance & Path Optimization: Drones learn to navigate complex environments autonomously.

✅ Performance Benchmarking: Compares MARLPPO against Single-Agent PPO and Multi-Agent SAC models.


🏗 Project Structure

📂 Multi-Agent-Drone-Surveillance

│── My_project   # project-related file

│── results      # Training logs and performance graphs

│── config.yaml  # configuration file required for RL learning

│── README.md    # Project documentation

|── pdf          # Conference paper 


🛠 Installation & Setup

1️⃣ Install Unity & ML-Agents

Make sure you have Unity ML-Agents installed. Follow these steps:

pip install mlagents

pip install mlagents-envs

2️⃣ Clone the Repository

git clone https://github.com/BanavathuGopi/MarlPPO.git

cd MarlPPO

3️⃣ Run the Unity Environment

Open Unity_Environment/ in Unity.

Ensure that mlagents-learn is configured correctly.

Ensure that the environment is visible properly if not download the required packages.

4️⃣ Train MARLPPO Model

Run the training script:

mlagents-learn config.yaml --run-id=test_1 --train

#In the terminal it will show that it is linked with the unity environment

Then click the play button in Unity.


📌 Results & Visualization

Cumulative Reward Graphs: 📈 Shows performance improvements over training.

Unity Environment: This shows how the environment and drone look.

Flow diagrams: Shows how the drone avoids obstacles and also about PPO.


📝 Citation

If you use MARLPPO in your research, please consider citing:

Banavathu Gopi, Nanapu Viswesh & Dr. K.E. Srinivasa Desikan.

Multi-Agent Drone Surveillance Using Deep Reinforcement Learning in Urban Aerial Mobility.


🤝 Contributing

Contributions are welcome! If you’d like to improve the project, open an issue or submit a pull request.

4️⃣ Monitor Training Progress

Launch TensorBoard to visualize training logs:
tensorboard --logdir= results/your_test

🎯 Applications

🚔 Urban Surveillance & Security – Smart monitoring for crime prevention.
🆘 Disaster Management – Rapid assessment of affected areas.
🌿 Environmental Monitoring – Tracking deforestation, pollution, and climate changes.

📧 Contact
For any questions or suggestions, reach out via email or GitHub issues.
