# Numerical Analysis Portfolio

UTN – Facultad Regional Santa Fe
Coursework 2025

## Institution

**University:** Universidad Tecnológica Nacional (UTN)
**Faculty:** Facultad Regional Santa Fe (FRSF)
**Course:** Numerical Analysis

---

# 1. General Description

This repository contains the complete solutions for the practical assignments developed during the Numerical Analysis course.

The projects address complex engineering problems through the implementation of numerical algorithms using **Python and C++**, with a strong focus on:

* convergence analysis
* numerical stability
* computational error analysis

---

# 2. Practical Assignments Summary

## TP 1 – Signal and Systems Analysis

**Focus:** Solving systems of equations and root-finding problems.

**Techniques implemented**

* Iterative numerical methods
* Direct methods for linear systems

---

## TP 2 – Steganography (LSB and TF2D)

**Topics**

* Image processing in spatial and frequency domains

**Implementation**

* Message hiding using Least Significant Bit (LSB)
* Parity modification in TF2D coefficients using parameter delta

**Conclusion**

* Analysis of information loss caused by rounding errors.

---

## TP 3 – Root Finding in Nonlinear Functions

**Problem**

Computation of the real volume of CO₂ using the **Van der Waals equation**.

**Algorithms**

* Higher-order Newton method based on Taylor expansion up to the second derivative
* Combination with the **Bisection Method** for robustness

**Analysis**

* Convergence order comparison
* Sensitivity to initial conditions

---

## TP 4 – Image Processing and Curve Fitting

**Application**

Dynamic analysis of a **tin droplet impacting a substrate**.

**Techniques**

* Edge detection using Sobel and Canny
* Contour fitting using cubic splines
* Least squares polynomial approximation

**Results**

* Contact angle estimation
* Perimeter calculation
* Spreading factor analysis using high-speed sequences (20538 fps)

---

## TP 5 – Ordinary Differential Equations (ODE)

**Model**

Simulation of droplet dynamics using a damped oscillator model.

**Methods compared**

* Third-order Taylor method
* Runge-Kutta 5–6
* Predictor-Corrector methods (Adams–Bashforth–Moulton)

**Analysis**

* Computational cost vs numerical accuracy

---

## TP 6 – Flow in Porous Media (Richards Equation)

**Challenge**

Simulation of liquid transport in paper (capillary redistribution).

**Models implemented**

* Brooks-Corey diffusivity model
* Van Genuchten model

**Simulation**

* 1D and 2D finite difference solutions
* Stability analysis using the CFL condition

---

# 3. Technologies and Libraries

**Programming Languages**

* Python (Google Colab)
* C++ (Qt Framework)

**Libraries**

* NumPy – Numerical computation
* OpenCV – Image processing
* Matplotlib / Plotly – Visualization
* SciPy – Interpolation and numerical methods

**Analysis**

* Truncation error analysis
* Floating-point rounding error analysis

---

# 4. Code Links (Google Colab)

### TP 2 – Steganography

https://colab.research.google.com/drive/15xi-blam9UT6tYjOGIR0RaDS45aRrcx2?usp=sharing

### TP 3 – Root Finding

https://colab.research.google.com/drive/1tL1KS9Y5E7ZcvndGcN397UFX2SuasiMg?usp=sharing

### TP 4 – Curve Fitting and Splines

https://colab.research.google.com/drive/13LCBeTl6Z-oniJhLcmhpXPcP18TSa15d?usp=sharing

### TP 5 – Solving ODEs

https://colab.research.google.com/drive/1buBvsYPycUmXyJT7zzKj-L1YNVECIDJT?usp=sharing

### TP 6 – Richards Equation (2D)

https://colab.research.google.com/drive/11hAJ4gG9Dlrauhw6PG5tt9BUcnzvBEpr?usp=sharing
