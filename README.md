# Multi-access Edge Computing Scheduling under 6G using Reinforcement Learning

This repository presents an edge computing scheduling optimization model designed for remote education in 6G network environments. The approach leverages reinforcement learning to dynamically adapt to network conditions and learner variability, aiming to enhance the efficiency and quality of content delivery.

## 📌 Project Overview

The rapid evolution of digital education demands robust computational frameworks, particularly for remote learning scenarios. Traditional scheduling techniques often struggle to accommodate the dynamic nature of learner engagement and 6G's asynchronous content delivery.

This project addresses these challenges by introducing a **reinforcement learning-based scheduling model**, tailored to support:

- Learner variability and feedback adaptation
- Network environment uncertainty
- Real-time scheduling decisions

## 🧠 Core Methodology

The system builds upon the **Asynchronous Stochastic Transition Estimation Network (ASTEN)** framework, which integrates:

- **Learner State Estimation (LSE)**: Captures transitions in learner status based on feedback and behavioral signals.
- **Scheduling Policy Optimization**: Reinforcement learning selects optimal actions via reward signals and updated learner states.
- **Adaptive Mechanism**: Adjusts scheduling strategy according to real-time changes in learner interaction and network conditions.

## 🔍 Key Features

- **ASTEN-Driven Learning Agent**: Learns to predict and adapt to learner performance fluctuations.
- **Real-World Scheduling Simulation**: Evaluated through synthetic and practical remote education scenarios.
- **Challenge-Aware Modeling**: Considers both theoretical and real-world constraints including bandwidth variability and learner heterogeneity.

## 📈 Results

Empirical evaluations demonstrate that the proposed model:

- Significantly outperforms traditional fixed or heuristic-based scheduling methods.
- Mitigates the instability caused by highly asynchronous learning environments.
- Enhances learner satisfaction and system responsiveness.

## 🧪 Potential Applications

- 6G-powered remote education platforms
- Smart classrooms and personalized learning systems
- Edge computing applications in content delivery and user interaction modeling

## 🛠️ Technologies Used

- Python
- Reinforcement Learning (DQN / PPO variants)
- Edge Computing Simulation Tools
- Network Simulation Environments

## 📄 Keywords

6G, Reinforcement Learning, Edge Computing, Adaptive Scheduling, Learner Modeling, ASTEN, Remote Education, LSE
