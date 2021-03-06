# Introductory Course on Model Order Reduction 

Please download the [lecture notes](https://github.com/highlando/mor-shortcourse-SH/raw/gh-pages/lecture_notes.pdf) -- updates after every lecture

### Abstract: 

I will start my short course by introducing the class of Linear Time Invariant (LTI) systems and the control related system theory for them. Although LTI systems can be used to model many real life processes, the mathematical theory for control is very general. The second lecture will be on the fundamental motivations and mathematical notions of model reduction in general and for LTI in particular. This lecture will provide some illustrative examples for the use and results of model reduction. In the third lecture, I will introduce the fundamental model reduction approach that uses projections and explain several ways to compute these projections. A mathematical well understood projection method is Balanced Truncation (BT). The 4th lecture will introduce BT and discuss how it can be applied in practice. The last lecture contains some example on how the LTI related theory can be extended to so called differential-algebraic equations (DAEs) or descriptor systems. After introducing some basic concepts, I will show and explain recent results concerning the control of Navier-Stokes equations.

### Course of the Lecture
 1. [Introduction to Linear Time Invariant (LTI) Systems](#1-introduction-to-the-control-theory-of-linear-time-invariant-lti-systems), Sep. 2nd 
 2. [Introduction to Model Reduction of LTI Systems](#2-introduction-to-model-reduction-of-lti-systems), Sep. 7th
 3. [Model Reduction of LTI Systems via Projection](#3-model-reduction-of-lti-systems-via-projection), Sep. 9th 
 4. [Balanced Truncation](#4-balanced-truncation), Sep. 14th
 5. [Model Reduction for DAEs and Navier-Stokes Equations](#5-model-reduction-for-daes-and-navier-stokes-equations), Sep. 15th

### Little Chinese Dictionary

| Hello | 你好 |
--------|--------
| Matrix| 矩阵 |
| Vector| 向量 |
| Eigenvalue |特征值|
| Projection |投影|
| Subspace |子空间|
| Interpolation |插值|
| Model |模型|
| System |系统|
| Transfer function |传递函数|
| Stable |稳定|
| Truncation |截断|

##  1. Introduction to the Control Theory of Linear Time Invariant (LTI) Systems

#### Requirements
 * Basic notions from Linear Algebra
 * Basic notions from linear ODEs
 * Laplace transform

#### Contents of the lecture
 * Examples of LTI systems
 * State space representation
 * Transfer functions
 * Realizations 
 * Controllability, Observability

## 2. Introduction to Model Reduction of LTI Systems

#### Requirements
 * LTI systems 
 * Basic notions from Linear Algebra

#### Contents of the lecture
 * Examples of successful MOR 
 * Basic concepts and ideas of model reduction
 * Norms of systems


##  3. Model Reduction of LTI Systems via Projection
#### Requirements
 * LTI systems 
 * Basic notions from Linear Algebra

#### Contents of the lecture
 * Projectors and projections
 * A projected model interpolates the transferfunction
 * Modal truncation
 * Dominant poles

##  4. Balanced Truncation

#### Requirements
 * LTI systems
 * Realizations
 * MOR via projection

#### Contents of the lecture
 * System Gramians and Lyapunov Equations
 * Balanced Realizations
 * Hankel Singular Values
 * Balanced Truncation
 * Hankel Operator


##  5. Model Reduction for DAEs and Navier-Stokes Equations

#### Requirements
 * LTI Systems
 * Balanced Truncation

#### Contents of the lecture
 * DAEs as LTI systems
 * Decouplings of DAEs
 * (Linearized) Navier-Stokes Equations
 * Balanced Truncation for linear Navier-Stokes Equations
 * Application to stabilization of flows

