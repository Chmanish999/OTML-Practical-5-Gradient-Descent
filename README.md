# OTML Practical 5: Gradient Descent

## 1. Aim

The aim of this practical is to understand Gradient Descent as an optimization technique used for learning the parameter of a simple machine learning model.

In this practical, students implement Gradient Descent for a simple linear model and observe how the parameter value is updated iteratively to reduce prediction error.

---

## 2. Course and Module Mapping

**Course:** A8751 – Optimization Techniques in Machine Learning  
**Module:** Module 1 – Model Fitting and Error Measurement  
**Practical Topic:** Gradient Descent for Linear Model Parameter Learning

This practical is mapped with Module 1 of OTML, where students study model fitting, error measurement, parameter estimation, and optimization-based learning.

---

## 3. Theory Background

Gradient Descent is one of the most important optimization algorithms used in machine learning.

In machine learning, a model makes predictions using some parameters. Initially, these parameters may not be correct. Because of this, the model may produce inaccurate predictions.

Gradient Descent improves the parameter values step by step so that the prediction error becomes smaller.

In this practical, a simple linear model is considered:

```text
ŷ = θx
