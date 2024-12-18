# diffusion2D

## Instructions for students

Please follow the instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

## Project description

This code solves the diffusion equation in 2D over a square domain which is at a certain temperature and a circular disc at the center which is at a higher temperature. This code solves the diffusion equation using the Finite Difference Method. The thermal diffusivity and initial conditions of the system can be changed by the user. The code produces four plots at various timepoints of the simulation. The diffusion process can be clearly observed in these plots.

## Installing the package

### Using pip3 to install from PyPI

`` pip install -i https://test.pypi.org/simple/ jafarkmi-diffusion2d==0.0.7``

### Required dependencies

matplotlib and numpy

## Running this package

```python
from jafarkmi_diffusion2d import solve
# intervals in x-, y- directions, mm
dx = dy = 0.1
# Thermal diffusivity of steel, mm^2/s
D = 4.

diffusion2d.solve(dx,dy,D)
```

## Citing

[pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md)
