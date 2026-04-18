# From Zero to PPO in RL

[![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github)](https://github.com/qipiao/From-Zero-to-PPO-in-RL)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python&logoColor=white)]()

> 从零开始学习PPO算法，包含**理论讲义、视频教程、代码实现**。

## 📋 项目简介

本项目是从零开始学习强化学习PPO算法的**完整自学笔记与实践库**。以《Mathematical Foundations of Reinforcement Learning》为理论主线，系统梳理强化学习知识体系，并提供配套 B 站视频讲解与可直接运行的 Python 代码。

**核心目标**：记录学习经历，帮助学习者从零开始，循序渐进地掌握强化学习理论，并能动手实现经典算法（包括 DQN、A2C、TRPO、PPO 等）。

## 🎯 项目内容

### 1. 📚 理论文档 (Beamer Slides)
- **完整 LaTeX Beamer 讲义**（PDF）
- 覆盖核心知识点：
  - 强化学习基础概念（MDP、贝尔曼方程、价值函数）
  - 基于模型算法（策略迭代）
  - 无模型算法（MC、TD、SARSA、Q-learning）
  - 深度强化学习（DQN、经验回放、目标网络）
  - 策略梯度方法（REINFORCE、Actor-Critic、A2C、TRPO、PPO）

### 2. 🎥 视频教程 (Bilibili)
- **基础学习视频**：
  - [西湖大学 赵世钰老师【强化学习的数学原理】](https://www.bilibili.com/video/BV1sd4y167NS/?spm_id_from=333.1387.0.0)
  - [「AI 第五季」RL 优化算法的基石：从 TRPO 到 PPO](https://www.bilibili.com/video/BV1V7cmzgENW/?spm_id_from=333.788.videopod.sections)
  - [强化学习PPO原理与推导](https://www.bilibili.com/video/BV1R5r4YkEkF/?spm_id_from=333.337.search-card.all.click)
- **自制讲解**：理论文档pdf讲解视频：[齐飘飘飘飘的B站主页](https://space.bilibili.com/401336562?spm_id_from=333.337.0.0)

### 3. 💻 代码实现 (Python)
- 经典强化学习算法的**干净、注释完整**的实现
- 基于 PyTorch + Gym 环境
- 包含算法：
  - 基础：Q-learning, SARSA
  - 深度：DQN
  - 策略梯度：A2C, TRPO, **PPO** 

## 📁 Directory Structure
```
From-Zero-to-PPO-in-RL/
├── code/                        # 各算法 Python 实现代码
│   ├── basics/      
│   ├── dqn/         
│   └── policy_gradient/  
├── From Zero to PPO in RL.pdf   # Beamer Slides
└── README.md                    # 项目说明
```

## 🎓 Reference
1. Shiyu Zhao. *Mathematical Foundations of Reinforcement Learning*, Springer, 2025
2. Schulman, et al. Trust Region Policy Optimization, 2015
3. Schulman, et al. Proximal Policy Optimization, 2017
