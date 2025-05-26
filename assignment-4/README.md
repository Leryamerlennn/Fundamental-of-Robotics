#  Assignment 4 – Dynamics of a 6-DOF Robot Manipulator

This notebook presents the full solution for assignment 4 of the *Fundamentals of Robotics* course. The objective was to derive the dynamic model of a 6-DOF manipulator (Stanford arm + spherical wrist) using the **Euler–Lagrange formulation**, and simulate joint torque requirements under motion.

All expressions were implemented symbolically and numerically from scratch, using previously developed kinematic models.

---

##  Objectives

1. Derive the full dynamic model using the Euler–Lagrange method
2. Compute:
   - Inertia matrix `M(q)`
   - Coriolis/centrifugal matrix `C(q, q̇)`
   - Gravity vector `g(q)`
3. Use joint-space trajectory from Assignment 3 to simulate motion
4. Apply a trapezoidal velocity profile for [0, π] joint motion
5. Plot torque requirements for each joint over time

---

##  Approach & Key Details

###  Dynamic Modeling

- Used the **Euler–Lagrange equation**
- Kinetic and potential energies were derived symbolically using `sympy`
- Dynamic parameters defined per joint (mass, inertia, center of mass, etc.)

###  Motion Simulation

- Simulated motion for all joints using a **trapezoidal velocity profile**  
- Computed time-series of joint positions, velocities, and accelerations
- Applied those into the dynamic equation to get torques

###  Torque Analysis

- Computed torque requirements over time for each joint
- Analyzed torque peaks, transitions, and mechanical effort needed

