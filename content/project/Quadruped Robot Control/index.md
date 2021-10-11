+++
# Date this page was created.
date = 2018-11-10T00:00:00
layout = "project"

# Project title.
title = "Quadruped Robot Control"

# Project summary to display on homepage.
summary = """
 Research Intern at Tencent RoboticsX.
 
 """
 
# image_preview = "MIPS_CPU/FPGA.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["AI","Robotics","CS"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# [header]
# image = "MIPS_CPU/FPGA.png"

+++

1.	Trained a deep reinforcement learning (PPO) model with reference motions to control a quadruped robot, Max, to walk in Pybullet.
2.	Applied Domain Randomization by randomizing dynamic parameters (friction, robot’s mass and etc.) during training. Successfully transferred the model to Gazebo and real-world environments.
3.	Introduced domain adaptation: predicting dynamic parameters using sequences of Max’s state, action data in Pybullet. Fed the predicted parameters for the PPO network and computed more adaptable control policies for Max’s locomotion. Obtained a 5.09% higher average reward in various environments in Gazebo compared with Robust DRL controller.
4.	Deployed the code in Tencent TLeague Framework, and nearly five times accelerated the training speed. During testing, realized a faster real-time control with C++ deep learning codes (Eigen).

