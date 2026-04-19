---
layout: single
title: Portfolio
permalink: /portfolio/
author_profile: false
---


## [Acrobatic obstacle avoidance for the TITA two-wheel legged robot](https://github.com/Emilianogith/TITA-dynamic-obstacle-avoidance)


<img src="/assets/images/projects/thesis/tita.png" alt="TITA robot" style="width: 70%; height: auto; display: block; margin: 0 auto;">

<img src="/assets/images/projects/thesis/3_obs.gif" alt="Jumping obstacle avoidance animation" style="width: 70%; height: auto; display: block; margin: 0 auto;">

This project was carried out as part of my Master’s degree thesis at the DIAG Robotics Lab of Sapienza University of Rome.  
It is an experimental research project focused on controlling an intrinsically unstable robotic platform for obstacle avoidance in highly demanding dynamic scenarios, under the supervision of Prof. Giuseppe Oriolo and Dr. Nicola Scianca.

- **Goal:** design a control framework to enable locomotion of an intrinsically unstable wheeled bipedal robot and perform dynamic obstacle avoidance through jumping.
- **Tools:** hierarchical control, Model Predictive Control (MPC), Kalman filtering, motion planning, C++, Python, ROS 2, Linux (Ubuntu), and MuJoCo.
- **Result:** the developed framework successfully enabled obstacle avoidance through jumping in general locomotion tasks and was validated in simulation with the MuJoCo physics engine. It was pushed to the robot’s maximum jump height limits and achieved acrobatic obstacle avoidance during high-speed locomotion. Experimental validation on the real platform is currently ongoing.
  

## [MPC for dynamic locomotion of the Lite3 quadruped robot](https://github.com/Emilianogith/MPC-for-dynamic-locomotion-in-the-MIT-cheetah-3)

<img src="/assets/images/projects/Lite3/trotting.gif" alt="Lite3" style="width: 70%; height: auto; display: block; margin: 0 auto;">

This project focuses on the development of a simulated quadruped locomotion framework based on Model Predictive Control. The framework was implemented in Python and validated in simulation using DARTpy with the Lite3 quadruped robot by DeepRobotics.

- **Goal:** design and validate an MPC-based control framework for dynamic quadruped locomotion, capable of generating stable walking behaviors under different gait conditions.
- **Tools:** Model Predictive Control, convex Quadratic Programming, Python, DARTpy, footstep planning, ground leg control, and swing leg control.
- **Result:** the developed framework successfully achieved stable and accurate quadruped locomotion in simulation. Different gaits were tested under various conditions, showing good robustness and effective walking performance.

## [MOD-RRT for real time planning in dynamic environments](https://github.com/Emilianogith/MOD-RRT-for-real-time-planning-in-dynamic-environments)


<img src="/assets/images/projects/MOD_RRT/obs_avoid.gif" alt="RRT" style="width: 70%; height: auto; display: block; margin: 0 auto;">

This project focuses on motion planning for mobile robots operating in dynamic environments, where safe and efficient navigation requires continuous adaptation to unforeseen obstacles. The work builds on MOD-RRT*, a sampling-based replanning algorithm capable of generating paths optimized for length and smoothness. The framework is implemented in Python using ROS and validated in simulation in Gazebo.

- **Goal:** extend the MOD-RRT* algorithm by incorporating robot dynamics, in order to generate dynamically feasible paths and perform real-time replanning for mobile robots in dynamic environments.
- **Tools:** MOD-RRT*, motion planning, dynamic replanning, robot dynamics, Python, ROS, and Gazebo.
- **Result:** the proposed framework improved the practical feasibility of the generated paths by taking robot dynamics into account, while maintaining the replanning capabilities of MOD-RRT* in dynamic environments. The approach was validated in simulation in Gazebo.

## [RL Hindsight goal ranking for pick and place tasks](https://github.com/Emilianogith/RL_project-Hindsight-Goal-Ranking-for-Pick-and-Place-tasks)

<img src="/assets/images/projects/RL/pick.png" alt="RL" style="width: 40%; height: auto; display: block; margin: 0 auto;">

This project focuses on the implementation and evaluation of a reinforcement learning approach for robotic manipulation in sparse reward environments, where learning successful behaviors is particularly challenging due to the limited feedback available to the agent. The approach is applied to a fixed-base manipulator performing a pick-and-place task in simulation, using the OpenAI Gym Fetch environment.

- **Goal:** implement and evaluate a reinforcement learning framework based on Hindsight Goal Ranking (HGR) for a robotic pick-and-place task in a sparse reward setting.
- **Tools:** reinforcement learning, Hindsight Goal Ranking (HGR), sparse reward learning, Python, OpenAI Gym, and the Fetch manipulation environment.
- **Result:** the project showed how Hindsight Goal Ranking can support more effective learning in sparse reward environments, improving the training process for a simulated robotic pick-and-place task.

## [Calibration of the kinematic parameters of a front-rear tricycle-like real robot](https://github.com/Emilianogith/Probabilistic_Robotics_project-4-Calibration_of_a_-real-_Robot)

This project was developed for the Probabilistic Robotics course and focuses on the calibration of a real front–rear tricycle-like mobile robot. The work addresses the estimation of both the robot’s kinematic parameters and the position of its onboard sensor.

- **Goal:** estimate and calibrate the kinematic parameters of a front–rear tricycle-like robot together with the position of its onboard sensor, in order to improve the accuracy of the robot model.
- **Tools:** C++, probabilistic robotics methods, parameter estimation, kinematic calibration, sensor calibration, Python.
- **Result:** the project provided a calibrated model of the real robotic platform, improving the consistency between the robot’s measured behavior and its kinematic and sensing models.

## [Graph classification in context of noisy labeled Dataset](https://github.com/Emilianogith/noisy-graph-classification)

<img src="/assets/images/projects/noisy/architecture.png" alt="graph classification" style="width: 70%; height: auto; display: block; margin: 0 auto;">

This project builds on a provided baseline repository and focuses on improving model robustness in the presence of noisy labels. The work explores different training strategies and architectural choices to enhance prediction quality and generalization.

- **Goal:** improve the robustness and predictive performance of the baseline model under noisy-label conditions by exploring alternative loss functions, hyperparameter tuning, and ensemble strategies.
- **Tools:** Python, Deep Learning, Graph classification, pretraining and fine-tuning.
- **Result:** the project provided an extensive experimental analysis of different strategies for handling label noise, highlighting the impact of robust loss functions, architectural and hyperparameter choices, and ensemble inference on the final prediction performance.

## [Shared control of a teleoperated echographic probe](https://github.com/Emilianogith/Shared-control-of-a-teleoperated-echographic-probe)

<img src="/assets/images/projects/echo/linear_fast.gif" alt="shared control" style="width: 70%; height: auto; display: block; margin: 0 auto;">

This project explores the use of shared control for the teleoperation of an echographic probe integrated with the Franka Emika Panda robot. 

- **Goal:** develop a shared-control framework for the teleoperation of an echographic probe, improving precision, safety, and human–robot collaboration in medical imaging applications.
- **Tools:** manipulator, shared control, teleoperation, impedance control, Franka Emika Panda robot, MATLAB, Robotics System Toolbox.
- **Result:** the project demonstrated how shared control can improve cooperation between the operator and the robot during echographic probe manipulation, enabling safer, smoother, and more accurate assisted motion.


## [ROS simple planner](https://github.com/Emilianogith/simple_planner)

<img src="/assets/images/projects/RP/diag_plan.png" alt="RP" style="width: 70%; height: auto; display: block; margin: 0 auto;">

This project implements a path planning framework for ROS based on the A* algorithm, designed to generate safe paths by considering obstacle proximity through a precomputed distance map.

- **Goal:** create a simple and effective planner for static and localization-based navigation.
- **Tools:** ROS, C++, A*, AMCL.
- **Result:** safe and efficient path generation in both static and localized navigation scenarios.

## [Pedestrian Intention Estimation on JAAD Dataset](https://github.com/Emilianogith/CV_project)

<img src="/assets/images/projects/CV/cv.png" alt="CV" style="width: 70%; height: auto; display: block; margin: 0 auto;">

This project explores pedestrian intention estimation for autonomous driving using computer vision, with a focus on understanding pedestrian behavior in urban environments and improving prediction reliability under challenging conditions.

- **Goal:** improve the accuracy and robustness of pedestrian intention estimation for safer vehicle–pedestrian interaction.
- **Tools:** Python, computer vision, Deep Learning, CNNs, LSTMs, JAAD dataset.
- **Result:** a structured analysis of current methods, challenges, and optimization strategies for building more reliable and efficient pedestrian intention estimation systems.
