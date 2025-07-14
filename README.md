# mycobot_vision_navigation

# 🧠 MyCobot Pro 600 – Image-Based Path Planning & Maze Solving

This project implements two vision-based control pipelines for the **MyCobot Pro 600**, enabling the robot to follow a drawn path or solve a physical maze using camera input and inverse kinematics. Built with **ROS 2**, **OpenCV**, and a custom joint control system.

## ✨ Features

- 🎯 **Basic Path Following**: Detects a hand-drawn path and generates smooth joint trajectories
- 🧩 **Maze Solving**: Processes maze images, skeletonizes paths, and plans shortest routes with A*
- 🤖 **Inverse Kinematics Control**: Maps image-space keypoints to robot joint angles using calibrated transformation
- 🧪 **Simulation & Real-World Execution**: Compatible with RViz2 and real robot execution

---

## 🗂️ Project Structure

