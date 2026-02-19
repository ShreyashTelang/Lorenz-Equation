# Lorenz-Equation

# 🌪 Lorenz Attractor Simulation (Chaos Theory)

## 📌 Project Overview

This project visualizes the **Lorenz System of Differential Equations**, one of the most famous examples in chaos theory. It demonstrates:

- Sensitive dependence on initial conditions  
- Deterministic chaos  
- Strange attractors  
- Nonlinear dynamical systems behavior  

The project includes:

- ✅ Static 3D visualization of the Lorenz attractor  
- ✅ Animated trajectories for multiple nearby initial conditions  
- ✅ Numerical integration using Runge–Kutta (RK45)  

---

## 🧠 What is the Lorenz Equation?

The Lorenz system was introduced in 1963 by meteorologist Edward N. Lorenz while studying atmospheric convection.

It is a system of three coupled nonlinear differential equations:

dx/dt = sigma(y − x)

dy/dt = x(rho − z) − y

dz/dt = xy − beta*z

Where:

- x → Convection intensity  
- y → Temperature difference  
- z → Vertical temperature distortion  

### Standard Parameters Used:

- sigma = 10  
- rho = 28  
- beta = 8/3  

These values produce chaotic behavior.

---

## 🌪 What is the Lorenz Attractor?

The Lorenz attractor is a strange attractor with a butterfly-shaped structure in 3D phase space.

Key properties:

- Deterministic system (no randomness)
- Extremely sensitive to initial conditions
- Long-term behavior is unpredictable
- Fractal-like structure
- Positive Lyapunov exponent

This phenomenon is famously known as:

🦋 The Butterfly Effect

---

## 🔬 Sensitive Dependence on Initial Conditions

Three very close initial conditions are used:

[5.0, 5.0, 5.0]  
[5.1, 5.1, 5.2]  
[4.8, 5.0, 4.8]

Even though they start very close together, their trajectories diverge rapidly over time.

This demonstrates:

- Exponential divergence  
- Chaos in deterministic systems  
- Limits of predictability  

---

## 🛠 Technologies Used

- Python  
- NumPy  
- SciPy (solve_ivp)  
- Matplotlib (3D plotting & animation)  

Numerical Method Used:

- RK45 (Adaptive Runge–Kutta Method)

---


