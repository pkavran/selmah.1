---
title: "SELMAH (Spectral Element MAgnetoHydrodynamics)"
permalink: /
---

# SELMAH (Spectral Element MAgnetoHydrodynamics)

SELMAH is a spectral element code developed as part of a PhD project for simulating incompressible fluid dynamics and nonlinear magnetohydrodynamic (MHD) equations. It is designed to solve the incompressible Navier–Stokes equations and MHD instabilities in complex geometries. The code is implemented in C++ and optimized for parallel computation in distributed memory environments.

## Features

- **2D and 3D Solvers**: 
  - Semi-implicit Continuous Galerkin Spectral Element solver for Incompressible Navier–Stokes equations
  - Explicit Discontinuous Galerkin Spectral Element solver for Maxwell-equations
  - Explicit Discontinuous Galerkin Spectral Element solver for Euler-equations, shock-capturing by artificial viscosity
  - Explicit and semi-implicit Continuous and Discontinuous Galerkin Spectral Element solver for MHD flows

- **Parallel and Distributed Computing**: 
  - Parallelized using MPI and PETSc
  - Domain decomposition based on Metis for problem partitioning

- **Mesh Generation**: 
  - Supports geometry creation via GAMBIT and GMSH mesh generators
  - Compatible with 4-, 9-, 8-, and 27-node hexahedral elements

- **Output**: 
  - Results output in Ensight 6 format for post-processing with Paraview or other visualization tools

## Videos

[![Watch the video](http://i3.ytimg.com/vi/SNN4Wb0S-3g/hqdefault.jpg)](https://youtu.be/SNN4Wb0S-3g)

[![Watch the video](http://i3.ytimg.com/vi/GDnA4Z6fUNU/hqdefault.jpg)](https://youtu.be/GDnA4Z6fUNU)

[![Watch the video](http://i3.ytimg.com/vi/JB1vvxUFU9k/hqdefault.jpg)](https://www.youtube.com/watch?v=JB1vvxUFU9k)

[![Watch the video](http://i3.ytimg.com/vi/ug1HFOyjuIc/hqdefault.jpg)](https://youtu.be/ug1HFOyjuIc)

[![Watch the video](http://i3.ytimg.com/vi/pRj0MMali0Y/hqdefault.jpg)](https://youtu.be/pRj0MMali0Y)

[![Watch the video](http://i3.ytimg.com/vi/_1OCx3eRYrE/hqdefault.jpg)](https://youtu.be/_1OCx3eRYrE)

[![Watch the video](http://i3.ytimg.com/vi/AlxMUHqUlc8/hqdefault.jpg)](http://www.youtube.com/watch?v=erLk59H86ww)

[![Watch the video](http://i3.ytimg.com/vi/eACH6_-J-3g/hqdefault.jpg)](https://www.youtube.com/watch?v=eACH6_-J-3g)

## Publications and Presentations

- Péter Kávrán, Gusztáv Mayer, Gábor Házi: *Hydrodynamics around a spacer of a VVER-440 Fuel Rod Bundle*, Proceedings of International Conference Nuclear Energy for New Europe, Portoroz, Slovenia. 

- Gábor Házi, Péter Kávrán: *On the cubic deviations in lattice Boltzmann methods*, Journal of Physics A: Math. Gen. 39 (2006), 3127–3136.

- Péter Kávrán: *Spectral Element Code Development for Incompressible Flow Simulations In the Subchannel of a Fuel Rod Bundle*, Proceedings of 16th AER Symposium (2006). [pdf in original README]

- Péter Kávrán: *Spectral Element Code Development for Magnetohydrodynamic Simulations*, 3rd Hungarian Plasma Physics and Fusion Technology Workshop, 20–21 April 2006. [ppt in original README]

- Péter Kávrán: *Spectral Element Code Development for Incompressible Flow Simulations*, presentation at CIEMAT, Madrid, Spain, 8 Oct 2006.

- Péter Kávrán: *Presentation at HLRS, Stuttgart*, 4 April 2007. [pdf in original README]

## Contact

www.linkedin.com/in/peter-kavran-07aab622

---
Generated from README.md of pkavran/selmah.1
