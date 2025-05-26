# 🤖 Fundamental of Robotics – Assignments Portfolio

This repository contains a series of practical assignments completed as part of the **"Fundamentals of Robotics"** course. Each task focuses on a different aspect of robotic manipulation: from kinematics and trajectory planning to dynamics.

These assignments demonstrate core competencies in robotic systems development — relevant to both low-level control (e.g., FK/IK, Jacobian, dynamics) and high-level motion planning (e.g., trajectory generation and synchronization). The code is written in Python, with symbolic and numerical solutions developed from scratch.

---

##  Contents

###  Assignment 1 – Forward & Inverse Kinematics ([Notebook](assignment-1/FR_ASSIGMENT_1.ipynb))
- **Model Used:** Stanford Manipulator + Spherical Wrist
- Coordinate frame assignment
- Forward Kinematics using transformation matrices
- Inverse Kinematics with validation on 50+ random joint configs
- Workspace visualization
- Class-based robot model with FK/IK methods

---

###  Assignment 2 – Differential Kinematics ([Notebook](assignment-2/FR_Assigment_2.ipynb))
- Jacobian matrix derivation
- Elbow and wrist singularities analysis
- End-effector velocity via direct and inverse Jacobian
- Numerical integration over time steps
- Trajectory comparison with different time steps

---

###  Assignment 3 – Trajectory Planning ([Notebook](assignment-3/FR_Assigment_3.ipynb))
- Joint space trajectory with position/velocity/acceleration plots
- Joint synchronization (6 DOF) with 120 Hz controller
- Error analysis in EE motion
- Polynomial interpolation for multiple points
- Cartesian straight-line planning using IK + sampling

---

###  Assignment 4 – Robot Dynamics ([Notebook](assignment-4/FR_Assigment_4.ipynb))
- Dynamic model using Euler-Lagrange method:
  - Inertia matrix `M(q)`
  - Coriolis matrix `C(q, q̇)`
  - Gravity vector `g(q)`
- Torque calculation using trapezoidal motion profile

---

##  Technologies

- Python (Jupyter Notebook)
- `numpy`, `sympy`, `matplotlib`
- (Optional) `pyvista` for 3D visualization (commented for Colab compatibility)



---

##  Author

**Valeria Neganova**  
Bachelor Robotics Engineer  
Focus: Low-level kinematics & dynamics, high-level trajectory planning  
📫 [Valerochka.neganova@mail.ru]  
