---
layout: post
title:  "ParkourBot: Adaptive Locomotion & Obstacle Navigation via Hierarchical Reinforcement Learning"
date:   2025-05-01 12:00:00 +00:00
image: /images/parkour.jpg
categories: UPenn
course: "ESE 650"
author: "Wenjing Mao"
video: https://www.youtube.com/watch?v=DPRVR94eFfw
paper:
code: https://github.com/taherk-robo/unitree_g1_ESE650?tab=readme-ov-file
---
ParkourBot extends the Unitree RL Gym with a two-tier hierarchical reinforcement learning pipeline that enables a Unitree G1 quadruped to walk and high-step through dense, obstacle-rich mazes. A high-level Q-learning planner reasons over a 3-D grid map to coordinate specialised low-level PPO gait controllers, producing parkour-style movements in simulation.