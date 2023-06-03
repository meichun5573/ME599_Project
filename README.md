# ME 599 Final Project — Solving Cart-Pole Swing-Up System Using MPC and RL
This repository contains the code and paper of the ME599 Final project.

## Group Members
William Lin, Joslyn Chen, John Cheng, Thomas Lin


## Abstract
The Cart-Pole Swing-up system is a challenging control problem where the goal is to swing up the pendulum from its initial downward position by controlling the cart's movement. We plan to address this challenge by employing both Model Predictive Control (MPC) and Reinforcement Learning (RL) techniques within the Python library to stabilize the system and achieve the desired control objectives.

## Cart-Pole Swing-up System 
In this project, the dynamics model of the inverted pendulum on a cart is referred from [Data Driven Science & Engineering](http://databookuw.com/databook.pdf). Based on the dynamics model, the state of the system is cart position, velocity, pendulum angle, and angular velocity, while the control input represents the force applied to the cart.  
<div align=center>
<img src="https://github.com/meichun5573/ME599_Project/blob/main/figure/cartpole.png?raw=true" width="600" height="400">
</div>  

## Model Predictive Control (MPC)
MPC is an advanced control technique that predicts system behavior, minimizing cost functions and satisfying constraints. With its adaptive nature and ability to handle constraints, MPC is well-suited for stabilizing the Cart-Pole system. In the scope of this study, we employ Scipy as our optimal problem solver.
<div align=center>
<img src="https://github.com/meichun5573/ME599_Project/blob/main/figure/MPC%20Flow%20Chart.JPG?raw=true" width="800" height="300">
</div>  

## Reinforcement Learning(RL) and Deep Q-network(DQN)
In this project, we apply RL using the OpenAI Gym environment and the DQN algorithm. By exploring and improving based on feedback, RL agents can discover effective strategies for stabilizing dynamic systems like the Cart-Pole system. Our approach incorporates a neural-network structured dynamics model implemented with Tensorflow.
<div align=center>
<img src="https://github.com/meichun5573/ME599_Project/blob/main/figure/DQN%20Flow%20Chart.JPG?raw=true" width="600" height="800">
</div>  

## Animative Result
<div align=center>
<img src="https://github.com/meichun5573/ME599_Project/blob/main/figure/MPC.gif?raw=true" width="600" height="400">
</div> 
