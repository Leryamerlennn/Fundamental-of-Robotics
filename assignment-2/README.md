#  Assignment 2 – Differential Kinematics and Jacobian Analysis

This assignment extends the Stanford + Spherical Wrist robot model from Assignment 1 by deriving and applying the **Jacobian matrix** to analyze differential motion, singularities, and the relationship between joint space and Cartesian space.

The focus is on velocity-level kinematics, numerical integration of joint motions, and evaluation of singular configurations using the Jacobian's structure.

---

##  Objectives

1. Derive the **Jacobian** matrix for a 6-DOF robot
2. Implement Jacobian-based forward and inverse velocity kinematics
3. Analyze **elbow** and **wrist singularities**
4. Numerically integrate motion with different step sizes
5. Validate the mapping from joint velocities to end-effector velocities and vice versa
6. Explore rank loss and null space behavior in singular configurations

---

##  Approach & Key Details

###  Jacobian Derivation

- The Jacobian was manually derived from the symbolic forward kinematics matrices
- The Jacobian matrix `J(q)` relates joint velocities `q̇` to end-effector velocities `ẋ`
  
