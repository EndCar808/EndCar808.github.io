---
date: '2021-12-29'
title: '2D Navier-Stokes Pseudospectral Solver'
github: 'https://github.com/EndCar808/2DNavierStokesSolver'
external: ''
tech:
  - C
  - MPI
  - FFTW
  - HDF5
  - Python
company: 'PhD Research'
showInProjects: true
---

A parallel pseudospectral solver for the 3D periodic Navier-Stokes equation in C. Fourier transforms performed via distributed memory are handled using the [FFTW](https://www.fftw.org/). Parallel I/O is handled using the [HDF5](https://www.hdfgroup.org/downloads/hdf5/) library. Data analysis and visualization is done in Python.
