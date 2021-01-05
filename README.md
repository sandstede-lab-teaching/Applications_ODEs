# Jupyter Notebooks with applications of ODEs
This repository contains Jupyter notebooks written in Python that illustrate the use of ODEs in applications:

* Chaotic Dynamics: visualize chaotic attractors in the Lorewnz and Rössler models
* Nonlinear pendulum: compute solutions to the nonlinear pendulum (mouse clicks define initial position and velocity) and animate them using a pendulum
* SIR model: visualizes solutions to SIR models and compares them with COVID-19 data
* Tipping points: provides interactive explorations of saddle-node bifurcations, tipping points, and hysteresis in models of budworm populations and global climate energy balances
* Yeast model: explores the logistic equations and fits its solutions to experimenbtal yeast growth data.

These notebooks run on a JupyterLab (which can be installed using, for instance, [Anaconda](https://www.anaconda.com)) with a Python 3 kernel. The notebooks require the modules ipywidgets, math, matplotlib, numpy, and scipy. If IPython is used, replace `%matplotlib widget` with `%matplotlib notebook` in each notebook.
