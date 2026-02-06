# bifurcation_logistic_map
# Bifurcation Diagram of the Logistic Map (Python)

This repository contains a python implementation for generating the
bifurcation diagram of the discrete logistic map

xₙ₊₁ = r xₙ (1 − xₙ)

The script illustrates how changes in the bifurcation parameter `r`
affect the long-run behavior of the system, including period-doubling
and the onset of chaos.

## Features
- Removal of transient dynamics
- High-resolution bifurcation plot
- Fully parameterized r-range
- Clean and well-documented R code

## Usage
Run the script and provide:
- Minimum value of `r`
- Maximum value of `r`

Example:
```r
Enter the minimum value of r: 2.5
Enter the maximum value of r: 4
