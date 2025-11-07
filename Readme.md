# 🔬 Flam Research & Development / AI — Assignment Submission

## 🧭 Objective
The goal of this assignment is to estimate the **unknown parameters** (θ, M, X) of a given parametric curve such that it best fits the provided dataset (`xy_data.csv`).  
The fitting quality is measured using the **L1 distance** between the predicted curve and the given data points.

---

## 🧮 Problem Definition

Given parametric equations:

\[
x(t) = t\cos(\theta) - e^{M|t|}\sin(0.3t)\sin(\theta) + X
\]
\[
y(t) = 42 + t\sin(\theta) + e^{M|t|}\sin(0.3t)\cos(\theta)
\]

Unknowns are:
- θ (rotation angle)
- M (exponential coefficient)
- X (offset constant)

where `6 ≤ t ≤ 60`, and parameters are constrained by:
