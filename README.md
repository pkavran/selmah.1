# SELMAH (Spectral Element MAgnetoHydrodynamics)

SELMAH is a spectral element code developed as part of a PhD project for simulating incompressible fluid dynamics and nonlinear magnetohydrodynamic (MHD) equations. It is designed to solve the incompressible Navier-Stokes equations and MHD instabilities in complex geometries. The code is implemented in C++ and optimized for parallel computation in distributed memory environments.

## Features

- **2D and 3D Solvers**: 
  - Semi-implicit Continuous Galerkin Spectral Element solver for incompressible flows
  - Explicit and semi-implicit Continuous and Discontinuous Galerkin Spectral Element solver for MHD flows
  - Explicit Discontinuos Galerkin solver for Maxwell-equations
- **Parallel and Distributed Computing**: 
  - Parallelized using MPI and PETSc
  - Domain decomposition based on Metis for problem partitioning
- **Mesh Generation**: 
  - Supports geometry creation via GAMBIT and GMSH mesh generators
  - Compatible with 4-, 9-, 8-, and 27-node hexahedral elements
- **Output**: 
  - Results output in Ensight 6 format for post-processing with Paraview or other visualization tools

## Publications and Presentations

- **Péter Kávrán, Gusztáv Mayer, Gábor Házi**: *Hydrodynamics around a spacer of a VVER-440 Fuel Rod Bundle*, Proceedings of International Conference Nuclear Energy for New Europe, Portoroz, Slovenia, Sept. 6-9 2004.[pdf](http://www.iaea.org/inis/collection/NCLCollectionStore/_Public/37/086/37086800.pdf?r=1)
  
- **Gábor Házi, Péter Kávrán**: *On the cubic deviations in lattice Boltzmann methods*, Journal of Physics A: Math. Gen. 39 (2006), 3127-3136.

- **Péter Kávrán**: *Spectral Element Code Development for Incompressible Flow Simulations In the Subchannel of a Fuel Rod Bundle*, Proceedings of 16th AER Symposium (2006).[pdf](http://www.iaea.org/inis/collection/NCLCollectionStore/_Public/37/086/37086800.pdf?r=1)

- **Péter Kávrán**: *Spectral Element Code Development for Magnetohydrodynamic Simulations*, 3rd Hungarian Plasma Physics and Fusion Technology Workshop, 20-21 April 2006.[ppt](https://docs.google.com/presentation/d/1jMfcwHBpwUTAbSxJ5_W55iYgJ4wLz3-Y/edit?usp=share_link&ouid=115990964241051061048&rtpof=true&sd=true)

- **Péter Kávrán**: *Spectral Element Code Development for Incompressible Flow Simulations*, presentation at CIEMAT, Madrid, Spain, 8 Oct 2006.

- **Péter Kávrán**: *Presentation at HLRS, Stuttgart*, 4 April 2007.[pdf](https://docs.google.com/presentation/d/1tlKASPawLIMt0xye7AHZ0JUkAMEfKpal/edit?usp=share_link&ouid=115990964241051061048&rtpof=true&sd=true)

## Movies
[![Watch the video](http://i3.ytimg.com/vi/JB1vvxUFU9k/hqdefault.jpg)](https://www.youtube.com/watch?v=JB1vvxUFU9k)

[![Watch the video](http://i3.ytimg.com/vi/ug1HFOyjuIc/hqdefault.jpg)](https://youtu.be/ug1HFOyjuIc)

[![Watch the video](http://i3.ytimg.com/vi/pRj0MMali0Y/hqdefault.jpg)](https://youtu.be/pRj0MMali0Y)

[![Watch the video](http://i3.ytimg.com/vi/_1OCx3eRYrE/hqdefault.jpg)](https://youtu.be/_1OCx3eRYrE)

[![Watch the video](http://i3.ytimg.com/vi/AlxMUHqUlc8/hqdefault.jpg)](http://www.youtube.com/watch?v=erLk59H86ww)

[![Watch the video](http://i3.ytimg.com/vi/eACH6_-J-3g/hqdefault.jpg)](https://www.youtube.com/watch?v=eACH6_-J-3g)

## Contact


