# 3D Visualization of the XOR Problem

This project demonstrates how the XOR problem, which is not linearly separable in 2D space, becomes linearly separable when transformed into 3D space by adding a new feature (x1*x2).


## Overview
The XOR (exclusive OR) problem is a classic example of a non-linearly separable dataset in machine learning. This repository shows:
- The original 2D XOR problem
- A 3D transformation that makes the data linearly separable
- Interactive 3D visualizations using Plotly

## Visualization
*(Example output - actual plot is interactive)*

## Technical Details
The transformation from 2D to 3D is achieved by adding a third dimension calculated as:
z = x1 * x2

