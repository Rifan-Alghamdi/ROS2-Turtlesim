# ROS2 Turtlesim Task 🐢

![ros2_showcase](images/ros2_showcase.png)

## 🧠 About the Project

This project demonstrates basic interaction with the [Turtlesim](https://docs.ros.org/en/ros2_packages/foxy/api/turtlesim.html) package in ROS2 (Robot Operating System 2). It was created as part of a summer training program to explore the fundamental components of ROS2 such as nodes, topics, and keyboard-based teleoperation.

Through this task, we:
- Launched a simulation window with a turtle avatar.
- Controlled the turtle in real time using keyboard arrows.
- Monitored active ROS2 topics and nodes in the system.
- Observed how commands are published and how ROS2 reacts live.

This simulation offers a simple yet powerful introduction to robotics software architecture and control.

---

## 🐢 Turtle Simulation Window

Below is the main turtlesim GUI window that shows the turtle in motion. The turtle was moved using arrow keys to trace a square path.

<img src="images/turtlesim_window.png" alt="Turtlesim Window" width="400"/>

---

## 📜 ROS2 Topics and Nodes

The following image shows the result of running terminal commands to list all active topics and nodes. These help us understand how data flows in ROS2.

<img src="images/ros2_topics_and_nodes.png" alt="ROS2 Topics and Nodes" width="400"/>

---

## ✅ How to Run This Task

Follow these steps to reproduce the project setup:

### 1. Set up Virtual Machine
- Install VirtualBox and Ubuntu MATE (recommended for lightweight performance).
- Enable copy-paste and shared folder access (install Guest Additions if needed).

### 2. Update the Systemsudo apt update
sudo apt upgrade

### 3. Install ROS2 (Humble)
Follow official instructions from: [https://docs.ros.org/en/humble/Installation.html](https://docs.ros.org/en/humble/Installation.html)

> Ensure environment variables are sourced correctly.

### 4. Run TurtleSim Node
Open a terminal and run:ros2 run turtlesim turtlesim_node
This launches the turtle simulation GUI.

### 5. Control the Turtle with Keyboard
Open another terminal and run:ros2 run turtlesim turtle_teleop_key
Use arrow keys to move the turtle. Try to trace basic shapes like a square or triangle.

### 6. View Active Topics
In any terminal:ros2 topic list

### 7. View Active Nodesros2 node list

---

## 🧾 Files in This Repo

| File Name                   | Description                                      |
|----------------------------|--------------------------------------------------|
| ros2_showcase.png         | Full terminal output showing ROS2 commands and results            |
| turtlesim_window.png      | TurtleSim window during motion                   |
| ros2_topics_and_nodes.png | Terminal showing topic/node list results         |

All images are placed inside the images/ folder.

---
