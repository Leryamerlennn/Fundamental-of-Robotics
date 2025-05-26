#  Assignment 1 – Forward and Inverse Kinematics (Stanford Manipulator + Spherical Wrist)

This notebook presents the complete solution for assignment 1 of the *Fundamentals of Robotics* course. The goal was to analytically model a 6-DOF manipulator using fundamental kinematic principles, without relying on built-in robotics libraries.

The manipulator consists of a **Stanford arm** as the elbow model, combined with a **spherical wrist**, allowing independent control of position and orientation in 3D space.

---

##  Objectives

1. Build a 6-DOF robotic manipulator kinematic model from scratch
2. Assign transformation matrices manually 
3. Derive the **forward kinematics** through matrix multiplication
4. Derive the **inverse kinematics** analytically
5. Validate IK by looping FK → IK → FK
6. Plot the reachable workspace and visualize robot configurations
7. Implement an OOP-style robot class containing all methods

---

##  Approach & Key Details

###  Model Structure

- **Arm**: Stanford-type (1 prismatic + 2 revolute joints)
- **Wrist**: Spherical (3 revolute joints)
- Full 6 DOF: 3 for position, 3 for orientation
