#  Assignment 3 – Trajectory Planning

This assignment focuses on generating smooth and synchronized **trajectories** for a 6-DOF robotic manipulator in both **joint space** and **Cartesian space**. It builds upon the kinematic foundation from Assignments 1 and 2 and transitions from static poses to motion planning with velocity and acceleration profiles.

---

##  Objectives
- Planned joint-space motion using trapezoidal and triangular velocity profiles
- Synchronized all joints to reach goals simultaneously
- Implemented cubic and higher-order polynomial interpolation
- Computed and visualized the effect of sampling error
- Planned straight-line Cartesian motion using two techniques:
  - Inverse Jacobian velocity control
  - IK-based path sampling
- Analyzed accuracy and compared ideal vs actual paths

---

##  Approach & Key Details

- Joint trajectories computed both continuously and using discrete control steps (120 Hz)
- Polynomial interpolation constrained to zero acceleration at boundaries
- Robot model and FK/IK methods reused from Assignments 1 and 2
- All plots show position, velocity, and trajectory deviation
