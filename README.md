<div align="center">

  <h1>🤖 mycobot_ros2</h1>
  <p><b>ROS 2 Jazzy Description Metapackage & URDF Visualizer for myCobot 280</b></p>

  <p>
    <a href="https://docs.ros.org/en/jazzy/"><img src="https://img.shields.io/badge/ROS2-Jazzy-blue?style=for-the-badge&logo=ros" alt="ROS 2 Jazzy"></a>
    <a href="http://wiki.ros.org/xacro"><img src="https://img.shields.io/badge/URDF-Xacro-orange?style=for-the-badge" alt="Xacro"></a>
    <a href="https://github.com/ManjariMeedeniya/mycobot_ros2/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License"></a>
  </p>

  <p>Developed as part of practical exploration in robot kinematics, kinematic modeling, and visualization within ROS 2.</p>

</div>

---

## 📌 Overview

This repository contains the `mycobot_ros2` metapackage and `mycobot_description` package for the **Elephant Robotics myCobot 280** 6-DOF articulated robotic arm. 

It provides complete **URDF/Xacro** kinematic models, high-resolution 3D visual `.dae` mesh assets, collision geometries, and customized launch configurations for inspecting and driving joint transformations in **RViz 2**.

---

## 🛠️ Package Structure

```text
mycobot_ros2/
├── mycobot_ros2/             # Metapackage configuration
│   └── package.xml
└── mycobot_description/      # Robot description package
    ├── launch/               # RViz2 visualization launch files
    ├── meshes/               # 3D visual & collision mesh assets (.dae)
    ├── rviz/                 # Display configuration files (.rviz)
    ├── urdf/                 # Kinematic macro definitions (.urdf / .xacro)
    ├── CMakeLists.txt
    └── package.xml
