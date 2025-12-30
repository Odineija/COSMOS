> COSMOS: Homogeneous and Isotropic Spaces

This repository, developed by **Aziz Aşar (Odineija)**, provides a computational framework for simulating and visualizing the geometric properties of cosmological manifolds. The project focuses on the **Cosmological Principle**, implementing numerical models for homogeneous and isotropic space
Overview

In theoretical cosmology, the Large-Scale Structure of the Universe is modeled using the Friedmann-Lemaître-Robertson-Walker (FLRW) metric. This project explores the mathematical representation of such spaces by calculating metric tensors and visualizing the resulting spatial curvature.


> Features

* **Metric Tensor Calculation**: Numerical computation of $g_{11}$, $g_{22}$, and $g_{12}$ components.
* **Volume Element Analysis**: Visualization of $\sqrt{|g|}$ (the metric determinant) to show spatial density.
* **Coordinate Singularity Mapping**: Demonstrates how geometric "stretching" occurs near the boundaries of specific projections.
* **Scientific Visualization**: High-resolution plots using the `plasma` colormap for intuitive understanding of gravitational/geometric potential.

> Mathematical Framework

The simulation calculates the line element for a curved surface:

$$ds^2 = g_{11} dx_1^2 + 2g_{12} dx_1 dx_2 + g_{22} dx_2^2$$

Where the metric components are derived from the constraint:
$$\text{denom} = \rho^2 - x_1^2 - x_2^2$$



> Prerequisites
* Python 3.x
* NumPy
* Matplotlib

> Installation
```bash
git clone [https://github.com/Odineija/COSMOS.git](https://github.com/Odineija/COSMOS.git)
cd COSMOS
