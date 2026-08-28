# 🤖 mycobot_ros2
**6-DOF Manipulator ROS 2 Kinematic Modeling**

> ⚠️ **Project Status: Ongoing / Learning Milestone**  
> *This repository is an ongoing project created as part of my learning journey in ROS 2 Jazzy, robot kinematics, and URDF/Xacro modeling. Core package architecture and asset integration are established, with full assembly modularization currently in progress.*

---

## 📌 Overview

This repository contains the `mycobot_ros2` metapackage and `mycobot_description` package for modeling a **myCobot 280 6-DOF robotic arm**. The goal of this project is to build modular, parametric URDF/Xacro description models and visualization pipelines for robotic manipulators within ROS 2.

---

## 🛠️ Current Implementation Progress

* **ROS 2 Infrastructure:** Created `mycobot_ros2` metapackage and `mycobot_description` package using `ament_cmake`.
* **CAD Asset Pipeline:** Integrated 3D COLLADA (`.dae`) mesh assets with configured build/export rules in `CMakeLists.txt` and `package.xml`.
* **Kinematic Modeling (In Progress):** Developing modular Xacro macro files to define 6-DOF link dynamics, mass/inertia matrices, and joint constraints.

---

## 🎯 Next Steps & Roadmap

* Complete full assembly integration (`mycobot_280.urdf.xacro`) combining base, 6-axis arm, and adaptive gripper macros.
* Resolve workspace dependencies using `rosdep`.
* Launch real-time joint state control and frame transformation visualization in **RViz 2**.
* Export kinematic tree diagrams via `urdf_to_graphiz`.

---

## 📜 License

Distributed under the BSD-3-Clause License.
