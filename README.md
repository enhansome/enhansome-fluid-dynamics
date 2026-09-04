# Awesome fluid dynamics with stars

![Awesome](logo/awesome-logo.svg)

A curated list of repositories related to fluid dynamics.

*`Please send pull requests or raise issues to improve this list.`*

## Contents

* [Educational](#educational)
  * [Notebooks](#notebooks)
  * [Lecture Series](#lecture-series)
  * [Books](#books)
* [Meshing](#meshing)
* [Computational Fluid Dynamics](#computational-fluid-dynamics)
  * [Finite Difference Methods (FDM)](#finite-difference-methods-fdm)
  * [Finite Element Methods (FEM)](#finite-element-methods-fem)
  * [Finite Volume Methods (FVM)](#finite-volume-methods-fvm)
  * [Spectral Methods](#spectral-methods)
  * [Vortex Methods / Panel Methods / Blade Element Methods](#vortex-methods--panel-methods--blade-element-methods)
  * [Immersed Boundary Methods (IBM)](#immersed-boundary-methods-ibm)
  * [Weather and Climate](#weather-and-climate)
  * [Building Energy and Urban Environments](#building-energy-and-urban-environments)
  * [Shallow Water / Ocean Dynamics](#shallow-water--ocean-dynamics)
  * [Lattice Boltzmann Methods (LBM)](#lattice-boltzmann-methods-lbm)
  * [Design and Optimization](#design-and-optimization)
  * [Coupling](#coupling)
  * [Chemical Kinetics](#chemical-kinetics)
  * [Supersonic / Hypersonic Flow](#supersonic--hypersonic-flow)
  * [Differential programming](#differential-programming)
  * [Neural Networks for PDE](#neural-networks-for-pde)
  * [Graphics](#graphics)
  * [Other Techniques](#other-techniques)
* [Experimental Fluid Dynamics](#experimental-fluid-dynamics)
  * [PIV / PTV](#piv--ptv)
  * [ML / Optical Flow](#ml--optical-flow)
* [Post-processing and Data Analysis](#post-processing-and-data-analysis)
* [Visualization](#visualization)
  * [2D Visualization](#2d-visualization)
  * [3D Visualization](#3d-visualization)
* [Benchmarks and Datasets](#benchmarks-and-datasets)
  * [Datasets](#datasets)
  * [Benchmarks](#benchmarks)
* [Reproducibility](#reproducibility)
* [Community](#community)
* [Related Topics](#related-topics)

## Educational

### Notebooks

* [barbagroup/CFDPython](https://github.com/barbagroup/CFDPython) ⭐ 4,125 | 🐛 33 | 🌐 Jupyter Notebook | 📅 2024-03-19 - A sequence of Jupyter notebooks featuring the "12 Steps to Navier-Stokes". ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/barbagroup/CFDPython/search?l=jupyter-notebook) ⭐ 4,125 | 🐛 33 | 🌐 Jupyter Notebook | 📅 2024-03-19
* [gpeyre/numerical-tours](https://github.com/gpeyre/numerical-tours) ⭐ 845 | 🐛 32 | 🌐 Jupyter Notebook | 📅 2025-04-10 - Numerical Tours of Signal Processing and other materials. ![MATLAB](logo/MATLAB.svg) ![Python](logo/Python.svg) ![Jupyter](logo/Jupyter.svg) ![julia](logo/julia.svg) ![R](logo/R.svg)
* [jfavre/Visualization-training](https://github.com/jfavre/Visualization-training) ⭐ 16 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-02-29 - The material used for the Scientific Visualization course, organized online by the Swiss National Supercomputing Centre (CSCS) on May 17-18, 2021. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/jfavre/Visualization-training/search?l=jupyter-notebook) ⭐ 16 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-02-29

### Lecture Series

* [rmcelreath/stat\_rethinking\_2022](https://youtube.com/playlist?list=PLDcUM9US4XdMROZ57-OIRtIK0aOynbgZN) - Statistical Rethinking (2022 Edition) by Richard McElreath. ![YouTube](logo/YouTube.svg) [![src](logo/src.svg)](https://github.com/rmcelreath/stat_rethinking_2022) ⭐ 4,109 | 🐛 12 | 🌐 R | 📅 2022-03-15
* [Machine Learning & Simulation/Fenics Tutorial](https://youtube.com/playlist?list=PLISXH-iEM4Jl0-G1CpvG-mhrV0233tG_D) - Fenics Tutorial lecture series. ![YouTube](logo/YouTube.svg) [![src](logo/src.svg)](https://github.com/Ceyron/machine-learning-and-simulation/tree/main/english/fenics) ⭐ 1,200 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2026-05-22
* [József Nagy/CFD basics](https://youtube.com/playlist?list=PLcOe4WUSsMkH6DLHpsYyveaqjKxnEnQqB) - CFD basics and introduction to OpenFOAM. ![YouTube](logo/YouTube.svg) [![src](logo/src.svg)](https://github.com/jnmlujnmlu/OpenFOAMTeaching) ⭐ 372 | 🐛 2 | 🌐 C++ | 📅 2024-01-26
* [Steve Brunton/Fluid Dynamics](https://www.youtube.com/playlist?list=PLMrJAkhIeNNQWO3ESiccZmPssvUDFHL4M) - Prof. Brunton's lecture series on *Fluid dynamics*. ![YouTube](logo/YouTube.svg)
* [Steve Brunton/Reinforcement Learning](https://youtube.com/playlist?list=PLMrJAkhIeNNQe1JXNvaFvURxGY4gE9k74) - Prof. Brunton's lecture series on *Reinforcement Learning*. ![YouTube](logo/YouTube.svg)
* [Steve Brunton/Vector Calculus and Partial Differential Equations](https://youtube.com/playlist?list=PLMrJAkhIeNNQromC4WswpU1krLOq5Ro6S) - Prof. Brunton's lecture series on *Vector Calculus and Partial Differential Equations*. ![YouTube](logo/YouTube.svg)
* [Barry Belmont/NSF Fluid Mechanics Series](https://www.youtube.com/playlist?list=PL0EC6527BE871ABA3) - A collection of NFS Fluid Mechanics lecutre series from mid 20th century. ![YouTube](logo/YouTube.svg)
* [The Bright Side of Mathematics/Functional analysis](https://youtube.com/playlist?list=PLBh2i93oe2qsGKDOsuVVw-OCAfprrnGfr) - Lecture series on *Functional analysis*. ![YouTube](logo/YouTube.svg)
* [MIT OpenCourseWare/MIT RES.6-012 Introduction to Probability, Spring 2018](https://www.youtube.com/playlist?list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6) - Lecture recording of *Probabilistic Systems Analysis and Applied Probability*. ![YouTube](logo/YouTube.svg)

### Books

* Castro, I. P., & Vanderwel, C. (2021). Turbulent Flows: An Introduction. IOP Publishing. [DOI :memo:](https://doi.org/10.1088/978-0-7503-3619-2) [Book :book:](https://github.com/cvanderwel/TurbulentFlows) ⭐ 20 | 🐛 0 | 🌐 MATLAB | 📅 2022-02-07
* Brunton, S., & Kutz, J. (2019). Data-Driven Science and Engineering: Machine Learning, Dynamical Systems, and Control. Cambridge: Cambridge University Press. [DOI :memo:](https://doi.org/10.1017/9781108380690) [Book :book:](http://databookuw.com/)
* Thuerey, N., Holl, P., Mueller, M., Schnell, P., Trost, F., & Um, K. (2021). Physics-based Deep Learning. [Book :book:](https://physicsbaseddeeplearning.org/)

## Meshing

* [CGAL/cgal](https://github.com/CGAL/cgal) ⭐ 6,033 | 🐛 685 | 🌐 C++ | 📅 2026-09-04 - The Computational Geometry Algorithms Library (CGAL) is a C++ library that aims to provide easy access to efficient and reliable algorithms in computational geometry. ![C++](logo/cpp.svg)
* [cnr-isti-vclab/meshlab](https://github.com/cnr-isti-vclab/meshlab) ⭐ 5,816 | 🐛 194 | 🌐 C++ | 📅 2026-08-25 - The open source mesh processing system. ![C++](logo/cpp.svg)
* [nschloe/meshio](https://github.com/nschloe/meshio) ⭐ 2,327 | 🐛 250 | 🌐 Python | 📅 2024-07-23 - I/O for exhaustive number of mesh file types. ![Python](logo/Python.svg)
* [PyMesh/PyMesh](https://github.com/PyMesh/PyMesh) ⭐ 2,044 | 🐛 251 | 🌐 C++ | 📅 2024-08-08 - Geometry Processing Library for Python. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
* [nschloe/pygmsh](https://github.com/nschloe/pygmsh) ⭐ 969 | 🐛 60 | 🌐 Python | 📅 2023-10-04 - Gmsh for Python. ![Python](logo/Python.svg)
* [nschloe/optimesh](https://github.com/nschloe/optimesh) ⭐ 636 | 🐛 3 | 📅 2026-05-18 - Mesh optimization, mesh smoothing. ![Python](logo/Python.svg)
* [inducer/meshpy](https://github.com/inducer/meshpy) ⭐ 588 | 🐛 18 | 🌐 C++ | 📅 2026-09-02 - 2D/3D simplicial mesh generator interface for Python (Triangle, TetGen, gmsh). ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
* [gmsh](https://en.wikipedia.org/wiki/Gmsh) - A three-dimensional finite element mesh generator with built-in pre- and post-processing facilities ![C++](logo/cpp.svg). ![Python](logo/Python.svg) ![julia](logo/julia.svg)

## Computational Fluid Dynamics

### Finite Difference Methods (FDM)

* [p-costa/CaNS](https://github.com/p-costa/CaNS) ⭐ 275 | 🐛 0 | 🌐 Fortran | 📅 2026-09-03 - A code for fast, massively-parallel direct numerical simulations (DNS) of canonical flows. ![FORTRAN](logo/FORTRAN.svg)

### Finite Element Methods (FEM)

* [KratosMultiphysics/Kratos](https://github.com/KratosMultiphysics/Kratos) ⭐ 1,358 | 🐛 728 | 🌐 C++ | 📅 2026-09-04 - Kratos Multiphysics (A.K.A Kratos) is a framework for building parallel multi-disciplinary simulation software. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
* [FEniCS/dolfinx](https://github.com/FEniCS/dolfinx) ⭐ 1,191 | 🐛 125 | 🌐 C++ | 📅 2026-09-03 - Next generation FEniCS problem solving environment. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
* [firedrakeproject/firedrake](https://github.com/firedrakeproject/firedrake) ⭐ 670 | 🐛 457 | 🌐 Python | 📅 2026-09-04 - Firedrake is an automated system for the portable solution of partial differential equations using the finite element method (FEM). ![Python](logo/Python.svg)
* [kinnala/scikit-fem](https://github.com/kinnala/scikit-fem) ⭐ 655 | 🐛 10 | 🌐 Python | 📅 2026-09-04 - Simple finite element assemblers. ![Python](logo/Python.svg)
* [FluidityProject/fluidity](https://github.com/FluidityProject/fluidity) ⭐ 386 | 🐛 32 | 🌐 Fortran | 📅 2026-09-02 - An open-source computational fluid dynamics code with adaptive unstructured mesh capabilities. ![FORTRAN](logo/FORTRAN.svg)
* [JuliaFEM/JuliaFEM.jl](https://github.com/JuliaFEM/JuliaFEM.jl) ⭐ 275 | 🐛 9 | 🌐 Julia | 📅 2026-05-11 - The JuliaFEM software library is a framework that allows for the distributed processing of large Finite Element Models across clusters of computers using simple programming models. ![julia](logo/julia.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/JuliaFEM/JuliaFEM.jl/search?l=jupyter-notebook) ⭐ 275 | 🐛 9 | 🌐 Julia | 📅 2026-05-11
* [deal.II](https://dealii.org/) - An open source finite element library. ![C++](logo/cpp.svg)

### Finite Volume Methods (FVM)

* [OpenFOAM/OpenFOAM-dev](https://github.com/OpenFOAM/OpenFOAM-dev) ⭐ 2,223 | 🐛 7 | 🌐 C++ | 📅 2026-09-04 - OpenFOAM is a free, open source computational fluid dynamics (CFD) software package released by the OpenFOAM Foundation. ![C++](logo/cpp.svg)
* [su2code/SU2](https://github.com/su2code/SU2) ⭐ 1,790 | 🐛 100 | 🌐 C++ | 📅 2026-09-04 - SU2: An Open-Source Suite for Multiphysics Simulation and Design. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
* [weymouth/WaterLily.jl](https://github.com/weymouth/WaterLily.jl) ⭐ 831 | 🐛 27 | 🌐 Julia | 📅 2026-09-01 -  Fast and simple fluid simulator in Julia. ![julia](logo/julia.svg)
* [cselab/aphros](https://github.com/cselab/aphros) ⭐ 460 | 🐛 14 | 🌐 C++ | 📅 2025-07-20 - Finite volume solver for incompressible multiphase flows with surface tension. ![C++](logo/cpp.svg)
* [MFlowCode/MFC](https://github.com/MFlowCode/MFC) ⭐ 417 | 🐛 123 | 🌐 Fortran | 📅 2026-09-04 - Exascale compressible multiphase flow solver with GPU acceleration (NVIDIA and AMD); 2025 Gordon Bell Prize Finalist. ![FORTRAN](logo/FORTRAN.svg)
* [ucns3d-team/UCNS3D](https://github.com/ucns3d-team/UCNS3D) ⭐ 358 | 🐛 48 | 🌐 Fortran | 📅 2026-08-04 - Unstructured Compressible Navier Stokes 3D code (UCNS3D). ![FORTRAN](logo/FORTRAN.svg)
* [code-saturne/code\_saturne](https://github.com/code-saturne/code_saturne) ⭐ 306 | 🐛 29 | 🌐 C++ | 📅 2026-08-30 - code\_saturne public mirror. ![C++](logo/cpp.svg) ![FORTRAN](logo/FORTRAN.svg) ![Python](logo/Python.svg)
* [nextfoam/Baram](https://github.com/nextfoam/baram) ⭐ 179 | 🐛 33 | 🌐 Python | 📅 2026-05-27 - BARAM is developed to mitigate the steep learning curve of Text-based Solvers. BARAM helps you focus on a problem itself with intuitive graphical user interface. For now, OpenFOAM® solvers modified by nextfoam are integrated into BARAM. ![Python](logo/Python.svg)
* [DelNov/T-Flows](https://github.com/DelNov/T-Flows) ⭐ 6 | 🐛 0 | 🌐 Fortran | 📅 2026-08-30 - T-Flows (stands for Turbulent Flows) is a Computational Fluid Dynamics (CFD) program, originally developed at Delft University of Technology, the Netherlands. ![FORTRAN](logo/FORTRAN.svg)

### Spectral Methods

* [DedalusProject/dedalus](https://github.com/DedalusProject/dedalus) ⭐ 704 | 🐛 65 | 🌐 Python | 📅 2026-07-21 - A flexible framework for solving PDEs with modern spectral methods. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/DedalusProject/dedalus/search?l=jupyter-notebook) ⭐ 704 | 🐛 65 | 🌐 Python | 📅 2026-07-21
* [Nek5000/Nek5000](https://github.com/Nek5000/Nek5000) ⭐ 486 | 🐛 80 | 🌐 Fortran | 📅 2026-08-13 - NEK5000 is an spectral element CFD code developed at the Mathematics and Computer Science Division of Argonne National Laboratory. ![FORTRAN](logo/FORTRAN.svg)
* [spectralDNS/shenfun](https://github.com/spectralDNS/shenfun) ⭐ 232 | 🐛 31 | 🌐 Python | 📅 2026-07-20 - High performance computational platform in Python for the spectral Galerkin method. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/spectralDNS/shenfun/search?l=jupyter-notebook) ⭐ 232 | 🐛 31 | 🌐 Python | 📅 2026-07-20
* [FourierFlows/FourierFlows.jl](https://github.com/FourierFlows/FourierFlows.jl) ⭐ 217 | 🐛 23 | 🌐 Julia | 📅 2026-06-29 - Tools for building fast, hackable, pseudospectral partial differential equation solvers on periodic domains. ![julia](logo/julia.svg)

### Vortex Methods / Panel Methods / Blade Element Methods

* [byuflowlab/FLOWUnsteady](https://github.com/byuflowlab/FLOWUnsteady) ⭐ 385 | 🐛 43 | 🌐 Julia | 📅 2026-08-05 - Mixed-fidelity unsteady aerodynamics and aeroacoustics. ![julia](logo/julia.svg)
* [camUrban/PteraSoftware](https://github.com/camUrban/PteraSoftware) ⭐ 266 | 🐛 40 | 🌐 Python | 📅 2026-09-03 - A fast, easy-to-use, and open-source software package for analyzing flapping-wing flight. ![Python](logo/Python.svg)
* [vortexmethods/VM2D](https://github.com/vortexmethods/VM2D) ⭐ 36 | 🐛 4 | 🌐 C++ | 📅 2026-09-03 - VM2D: Open-Source Code for 2D Flow Simulation by Using Meshless Lagrangian Vortex Methods. ![C++](logo/cpp.svg)
* [Applied-Scientific-Research/Omega2D](https://github.com/Applied-Scientific-Research/Omega2D) ⭐ 36 | 🐛 19 | 🌐 C++ | 📅 2025-02-15 - Two-dimensional flow solver with GUI using vortex particle and boundary element methods. ![C++](logo/cpp.svg)
* [markstock/vic2d](https://github.com/markstock/vic2d) ⭐ 33 | 🐛 0 | 🌐 C | 📅 2026-05-14 - Two-dimensional semi-Lagrangian vortex method for very low viscosity fluid simulation. ![C++](logo/cpp.svg) ![FORTRAN](logo/FORTRAN.svg)
* [gdeskos/DVMpp](https://github.com/gdeskos/DVMpp) ⭐ 14 | 🐛 1 | 🌐 C++ | 📅 2026-02-01 - 2D Discrete Vortex Method Code written in C++. ![C++](logo/cpp.svg)

### Immersed Boundary Methods (IBM)

* [IBAMR/IBAMR](https://github.com/IBAMR/IBAMR) ⭐ 444 | 🐛 178 | 🌐 C++ | 📅 2026-09-04 - An adaptive and distributed-memory parallel implementation of the immersed boundary (IB) method. ![C++](logo/cpp.svg)
* [ChenguangZhang/sdfibm](https://github.com/ChenguangZhang/sdfibm) ⭐ 201 | 🐛 7 | 🌐 C++ | 📅 2025-06-23 - Immersed boundary method empowered by signed distance field, and OpenFOAM. ![C++](logo/cpp.svg)
* [cwrowley/ibpm](https://github.com/cwrowley/ibpm) ⭐ 126 | 🐛 4 | 🌐 C++ | 📅 2020-03-21 - Immersed Boundary Projection Method (IBPM). ![C++](logo/cpp.svg)
* [barbagroup/PetIBM](https://github.com/barbagroup/PetIBM) ⭐ 119 | 🐛 1 | 🌐 C++ | 📅 2022-08-11 - PetIBM - toolbox and applications of the immersed-boundary method on distributed-memory architectures. ![C++](logo/cpp.svg)
* [barbagroup/cuIBM](https://github.com/barbagroup/cuIBM) ⭐ 94 | 🐛 8 | 🌐 Cuda | 📅 2023-03-26 - cuIBM: a GPU-based immersed boundary method code. ![C++](logo/cpp.svg)

### Weather and Climate

* [wrf-model/WRF](https://github.com/wrf-model/WRF) ⭐ 1,747 | 🐛 217 | 🌐 Fortran | 📅 2026-09-04 -  Weather Research and Forecasting (WRF) model is a numerical weather prediction (NWP) system designed to serve both atmospheric research and operational forecasting needs. ![FORTRAN](logo/FORTRAN.svg)

### Building Energy and Urban Environments

* [NREL/EnergyPlus](https://github.com/NREL/EnergyPlus) ⭐ 1,563 | 🐛 873 | 🌐 C++ | 📅 2026-09-04 - EnergyPlus™ is a whole building energy simulation program that engineers, architects, and researchers use to model both energy consumption and water use in buildings. ![C++](logo/cpp.svg)
* [ladybug-tools/butterfly](https://github.com/ladybug-tools/butterfly) ⭐ 262 | 🐛 100 | 🌐 Python | 📅 2022-12-27 - :butterfly: A light python API for creating and running OpenFoam cases for CFD simulation. ![Python](logo/Python.svg)
* [uDALES/u-dales](https://github.com/uDALES/u-dales) ⭐ 84 | 🐛 45 | 🌐 Jupyter Notebook | 📅 2026-08-30 - uDALES: large-eddy-simulation software for urban flow, dispersion and microclimate modelling. ![FORTRAN](logo/FORTRAN.svg)

### Shallow Water / Ocean Dynamics

* [CliMA/Oceananigans.jl](https://github.com/CliMA/Oceananigans.jl) ⭐ 1,412 | 🐛 356 | 🌐 Julia | 📅 2026-09-04 - Julia software for fast, friendly, flexible, data-driven, ocean-flavored fluid dynamics on CPUs and GPUs. ![julia](logo/julia.svg)
* [team-ocean/veros](https://github.com/team-ocean/veros) ⭐ 400 | 🐛 27 | 🌐 Python | 📅 2026-09-01 - The versatile ocean simulator, in pure Python, powered by JAX. ![Python](logo/Python.svg)
* [OceanParcels/parcels](https://github.com/OceanParcels/parcels) ⭐ 361 | 🐛 119 | 🌐 Python | 📅 2026-09-04 - Parcels (Probably A Really Computationally Efficient Lagrangian Simulator) is a set of Python classes and methods to create customisable particle tracking simulations using output from Ocean Circulation models. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/OceanParcels/parcels/search?l=jupyter-notebook) ⭐ 361 | 🐛 119 | 🌐 Python | 📅 2026-09-04
* [jostbr/shallow-water](https://github.com/jostbr/shallow-water) ⭐ 177 | 🐛 0 | 🌐 Python | 📅 2020-11-27 - Python model solving the shallow water equations (linear momentum, nonlinear continuity). ![Python](logo/Python.svg)

### Lattice Boltzmann Methods (LBM)

* [lanl/MF-LBM](https://github.com/lanl/MF-LBM) ⭐ 129 | 🐛 0 | 🌐 Fortran | 📅 2023-07-25 - A Portable, Scalable and High-performance Lattice Boltzmann Code for DNS of Flow in Porous Media. ![FORTRAN](logo/FORTRAN.svg)
* [aromanro/LatticeBoltzmann](https://github.com/aromanro/LatticeBoltzmann) ⭐ 55 | 🐛 3 | 🌐 C++ | 📅 2025-12-30 - A 2D Lattice Boltzmann program. ![C++](logo/cpp.svg)
* [unigespc/palabos](https://gitlab.com/unigespc/palabos) - Palabos is an open-source CFD solver based on the lattice Boltzmann method. ![C++](logo/cpp.svg)

### Design and Optimization

* [peterdsharpe/AeroSandbox](https://github.com/peterdsharpe/AeroSandbox) ⭐ 1,323 | 🐛 18 | 🌐 Jupyter Notebook | 📅 2026-07-05 - Aircraft design optimization made fast through modern automatic differentiation. ![Python](logo/Python.svg)
* [mdolab/dafoam](https://github.com/mdolab/dafoam) ⭐ 348 | 🐛 13 | 🌐 C | 📅 2026-08-09 - DAFoam: Discrete Adjoint with OpenFOAM for High-fidelity Gradient-based Design Optimization. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
* [DARcorporation/xfoil-python](https://github.com/DARcorporation/xfoil-python) ⭐ 112 | 🐛 16 | 🌐 Fortran | 📅 2021-06-16 - Stripped down version of XFOIL as compiled python module. ![Python](logo/Python.svg)

### Coupling

* [precice/precice](https://github.com/precice/precice) ⭐ 967 | 🐛 244 | 🌐 C++ | 📅 2026-09-01 - A coupling library for partitioned multi-physics simulations, including, but not restricted to fluid-structure interaction and conjugate heat transfer simulations. ![C++](logo/cpp.svg)

### Chemical Kinetics

* [Cantera/cantera](https://github.com/Cantera/cantera) ⭐ 848 | 🐛 56 | 🌐 C++ | 📅 2026-09-03 - Chemical kinetics, thermodynamics, and transport tool suite. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)

### Supersonic / Hypersonic Flow

* [matteobernardini/STREAmS](https://github.com/matteobernardini/STREAmS) ⭐ 96 | 🐛 2 | 🌐 Fortran | 📅 2022-12-01 - STREAmS performs Direct Numerical Simulations of compressible turbulent flows in Cartesian geometry solving the unsteady, fully compressible Navier-Stokes equations for a perfect gas. ![FORTRAN](logo/FORTRAN.svg)
* [sergeas67/OpenHyperFLOW2D](https://github.com/sergeas67/OpenHyperFLOW2D) ⭐ 93 | 🐛 0 | 🌐 C++ | 📅 2018-07-27 - 2D (flat/axisymmetrical) transient viscous compressible multicomponent sub/trans/supersonic reacting gas flow with RANS/URANS turbulence models. ![C++](logo/cpp.svg)

### Differential programming

* [taichi-dev/taichi](https://github.com/taichi-dev/taichi) ⭐ 28,359 | 🐛 926 | 🌐 C++ | 📅 2026-07-06 - Parallel programming for everyone. ![Python](logo/Python.svg)
* [tum-pbs/PhiFlow](https://github.com/tum-pbs/PhiFlow) ⭐ 1,931 | 🐛 30 | 🌐 Python | 📅 2026-07-16 - A differentiable PDE solving framework for machine learning. ![Python](logo/Python.svg)
* [google/jax-cfd](https://github.com/google/jax-cfd) ⭐ 963 | 🐛 31 | 🌐 Jupyter Notebook | 📅 2026-07-08 - Computational Fluid Dynamics in JAX. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/google/jax-cfd/search?l=jupyter-notebook) ⭐ 963 | 🐛 31 | 🌐 Jupyter Notebook | 📅 2026-07-08

### Neural Networks for PDE

* [lululxvi/deepxde](https://github.com/lululxvi/deepxde) ⭐ 4,408 | 🐛 316 | 🌐 Python | 📅 2026-08-18 - Deep learning library for solving differential equations and more. ![Python](logo/Python.svg)
* [google/neural-tangents](https://github.com/google/neural-tangents) ⚠️ Archived - Fast and Easy Infinite Neural Networks in Python. ![Python](logo/Python.svg)
* [SciML/NeuralPDE.jl](https://github.com/SciML/NeuralPDE.jl) ⭐ 1,222 | 🐛 155 | 🌐 Julia | 📅 2026-08-31 - Physics-Informed Neural Networks (PINN) and Deep BSDE Solvers of Differential Equations for Scientific Machine Learning (SciML) accelerated simulation. ![julia](logo/julia.svg)
* [isl-org/DeepLagrangianFluids](https://github.com/isl-org/DeepLagrangianFluids) ⚠️ Archived - Lagrangian Fluid Simulation with Continuous Convolutions. ![Python](logo/Python.svg)
* [maxjiang93/space\_time\_pde](https://github.com/maxjiang93/space_time_pde) ⭐ 108 | 🐛 1 | 🌐 Python | 📅 2021-01-28 - MeshfreeFlowNet: Physical Constrained Space Time Super-Resolution. ![Python](logo/Python.svg)

### Graphics

* [PavelDoGreat/WebGL-Fluid-Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation) ⭐ 16,609 | 🐛 75 | 🌐 JavaScript | 📅 2024-11-12 - Play with fluids in your browser (works even on mobile). ![JavaScript](logo/JavaScript.svg)
* [doyubkim/fluid-engine-dev](https://github.com/doyubkim/fluid-engine-dev) ⭐ 2,098 | 🐛 60 | 🌐 C++ | 📅 2023-12-24 - Fluid simulation engine for computer graphics applications. ![C++](logo/cpp.svg)

### Other Techniques

* [cornellius-gp/gpytorch](https://github.com/cornellius-gp/gpytorch) ⭐ 3,907 | 🐛 417 | 🌐 Python | 📅 2026-07-10 - A highly efficient and modular implementation of Gaussian Processes in PyTorch. ![Python](logo/Python.svg)
* [PyFR/PyFR](https://github.com/PyFR/PyFR) ⭐ 572 | 🐛 13 | 🌐 Python | 📅 2026-09-03 - Framework for solving advection-diffusion type problems on streaming architectures using the Flux Reconstruction approach of Huynh. ![Python](logo/Python.svg)
* [pencil-code/pencil-code](https://github.com/pencil-code/pencil-code) ⭐ 242 | 🐛 0 | 🌐 Fortran | 📅 2026-09-04 - A high-order finite-difference code for compressible hydrodynamic flows with magnetic fields and particles. ![FORTRAN](logo/FORTRAN.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/pencil-code/pencil-code/search?l=jupyter-notebook) ⭐ 242 | 🐛 0 | 🌐 Fortran | 📅 2026-09-04
* [NaluCFD/Nalu](https://github.com/NaluCFD/Nalu) ⭐ 163 | 🐛 11 | 🌐 C | 📅 2026-03-30 - Nalu: a generalized unstructured massively parallel low Mach flow code designed to support a variety of open applications of interest built on the Sierra Toolkit and Trilinos solver Tpetra solver stack. ![C++](logo/cpp.svg)
* [lesgo-jhu/lesgo](https://github.com/lesgo-jhu/lesgo) ⭐ 152 | 🐛 7 | 🌐 Fortran | 📅 2021-01-29 - The Large-Eddy Simulation framework from the Turbulence Research Group at Johns Hopkins University. ![FORTRAN](logo/FORTRAN.svg)

## Experimental Fluid Dynamics

### PIV / PTV

* [OpenPIV/openpiv-python](https://github.com/openpiv/openpiv-python) ⭐ 304 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2026-08-22 - OpenPIV consists in a Python and Cython modules for scripting and executing the analysis of a set of PIV image pairs. ![Python](logo/Python.svg) ![MATLAB](logo/MATLAB.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/OpenPIV/openpiv-python/search?l=jupyter-notebook) ⭐ 304 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2026-08-22
* [ronshnapp/MyPTV](https://github.com/ronshnapp/myptv) ⭐ 71 | 🐛 10 | 🌐 Python | 📅 2026-09-01 - Python based 3D-PTV - open source pure Python three-dimensional particle tracking velocimetry. ![Python](logo/Python.svg)
* [OpenPTV/openptv](https://github.com/openptv/openptv) ⭐ 46 | 🐛 17 | 🌐 C | 📅 2026-03-01 - OpenPTV - open source 3D-PTV software. ![C++](logo/cpp.svg)
* [OpenPTV/pyptv](https://github.com/openptv/pyptv) ⭐ 2 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-04-01 - Python GUI for OpenPTV - open source three-dimensional particle tracking velocimetry. ![Python](logo/Python.svg)
* [JHU-NI-LAB/OpenLPT\_Shake-The-Box](https://github.com/JHU-NI-LAB/OpenLPT_Shake-The-Box) - Open-source C++ code for Shake-the-box, particle tracking algorithm. ![C++](logo/cpp.svg) ![MATLAB](logo/MATLAB.svg)

### ML / Optical Flow

* [erizmr/UnLiteFlowNet-PIV](https://github.com/erizmr/UnLiteFlowNet-PIV) ⭐ 67 | 🐛 4 | 🌐 Python | 📅 2020-08-05 - Unsupervised learning of Particle Image Velocimetry. (ISC 2020). ![Python](logo/Python.svg)
* [shengzesnail/PIV-LiteFlowNet-en](https://github.com/shengzesnail/PIV-LiteFlowNet-en) ⭐ 51 | 🐛 0 | 🌐 C++ | 📅 2019-07-23 - Particle image velocimetry via a deep neural network (LiteFlowNet). ![C++](logo/cpp.svg) ![Python](logo/Python.svg) ![MATLAB](logo/MATLAB.svg)
* [yongleex/PIV-DCNN](https://github.com/yongleex/PIV-DCNN) ⭐ 25 | 🐛 0 | 🌐 MATLAB | 📅 2021-05-21 - Perform PIV image pair match using deep conv neural network. ![MATLAB](logo/MATLAB.svg) ![C++](logo/cpp.svg)

## Post-processing and Data Analysis

* [numpy/numpy](https://github.com/numpy/numpy) ⭐ 32,652 | 🐛 2,333 | 🌐 Python | 📅 2026-09-04 - The fundamental package for scientific computing with Python. ![Python](logo/Python.svg)
* [dynamicslab/pysindy](https://github.com/dynamicslab/pysindy) ⭐ 1,896 | 🐛 83 | 🌐 Python | 📅 2026-06-10 - A sparse regression package with several implementations for the Sparse Identification of Nonlinear Dynamical systems. ![Python](logo/Python.svg)
* [SURGroup/UQpy](https://github.com/SURGroup/UQpy) ⭐ 361 | 🐛 20 | 🌐 Python | 📅 2026-08-27 - UQpy (Uncertainty Quantification with python) is a general purpose Python toolbox for modeling uncertainty in physical and mathematical systems. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/SURGroup/UQpy/search?l=jupyter-notebook) ⭐ 361 | 🐛 20 | 🌐 Python | 📅 2026-08-27
* [mathLab/PyDMD](https://github.com/mathLab/PyDMD) ⭐ 128 | 🐛 0 | 🌐 Python | 📅 2025-03-06 - Python Dynamic Mode Decomposition. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/mathLab/PyDMD/search?l=jupyter-notebook) ⭐ 128 | 🐛 0 | 🌐 Python | 📅 2025-03-06
* [mengaldo/PySPOD](https://github.com/mengaldo/PySPOD) ⭐ 128 | 🐛 13 | 🌐 Jupyter Notebook | 📅 2026-07-20 - A Python package for spectral proper orthogonal decomposition (SPOD).  ![Python](logo/Python.svg)
* [ritchieng/eigenvectors-from-eigenvalues](https://github.com/ritchieng/eigenvectors-from-eigenvalues) ⭐ 97 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2021-11-03 - This repository implements a calculation of eigenvectors from eigenvectors elegantly through PyTorch. ![Jupyter](logo/Jupyter.svg)
* [belson17/modred](https://github.com/belson17/modred) ⭐ 83 | 🐛 17 | 🌐 Python | 📅 2021-05-04 - An easy-to-use and parallelized library for finding modal decompositions and reduced-order models. ![Python](logo/Python.svg)
* [Astroua/TurbuStat](https://github.com/Astroua/TurbuStat) ⭐ 69 | 🐛 21 | 🌐 Python | 📅 2025-01-06 - Statistics of Turbulence Python Package. ![Python](logo/Python.svg)
* [haller-group/LCStool](https://github.com/haller-group/LCStool) ⭐ 33 | 🐛 1 | 🌐 Matlab | 📅 2015-06-10 - LCStool: LCS Tool is a computational engine for analyzing fluid flows by extracting their most influential material surfaces, Lagrangian Coherent Structures. ![MATLAB](logo/MATLAB.svg)

## Visualization

### 2D Visualization

* [3b1b/manim](https://github.com/3b1b/manim) ⭐ 93,060 | 🐛 494 | 🌐 Python | 📅 2026-09-01 - Animation engine for explanatory math videos. ![Python](logo/Python.svg)
* [matplotlib/matplotlib](https://github.com/matplotlib/matplotlib) ⭐ 23,145 | 🐛 1,470 | 🌐 Python | 📅 2026-09-04 - matplotlib: plotting with Python. ![Python](logo/Python.svg)
* [mwaskom/seaborn](https://github.com/mwaskom/seaborn) ⭐ 14,010 | 🐛 230 | 🌐 Python | 📅 2026-07-06 - Statistical data visualization in Python. ![Python](logo/Python.svg)
* [garrettj403/SciencePlots](https://github.com/garrettj403/SciencePlots) ⭐ 9,196 | 🐛 19 | 🌐 Python | 📅 2026-06-23 - Matplotlib styles for scientific plotting. ![Python](logo/Python.svg)
* [scikit-image/scikit-image](https://github.com/scikit-image/scikit-image) ⭐ 6,581 | 🐛 947 | 🌐 Python | 📅 2026-09-04 - Image processing in Python. ![Python](logo/Python.svg)
* [lukelbd/proplot](https://github.com/lukelbd/proplot) ⭐ 1,147 | 🐛 95 | 🌐 Python | 📅 2025-02-27 - :art: A succinct matplotlib wrapper for making beautiful, publication-quality graphics. ![Python](logo/Python.svg)

### 3D Visualization

* [blender/blender](https://github.com/blender/blender) ⭐ 19,994 | 🐛 0 | 🌐 C++ | 📅 2026-09-04 - A free and open source 3D creation suite, supporting the entirety of the 3D pipeline-modeling, rigging, animation, simulation, rendering, compositing, motion tracking and video editing. ![Python](logo/Python.svg)
* [pyvista/pyvista](https://github.com/pyvista/pyvista) ⭐ 3,794 | 🐛 595 | 🌐 Python | 📅 2026-09-04 - 3D plotting and mesh analysis through a streamlined interface for the Visualization Toolkit (VTK). ![Python](logo/Python.svg)
* [K3D-tools/K3D-jupyter](https://github.com/K3D-tools/K3D-jupyter) ⭐ 1,034 | 🐛 2 | 🌐 Python | 📅 2026-09-03 - K3D lets you create 3D plots backed by WebGL with high-level API (surfaces, isosurfaces, voxels, mesh, cloud points, vtk objects, volume renderer, colormaps, etc). ![Python](logo/Python.svg) ![JavaScript](logo/JavaScript.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/K3D-tools/K3D-jupyter/search?l=jupyter-notebook) ⭐ 1,034 | 🐛 2 | 🌐 Python | 📅 2026-09-03
* [InsightSoftwareConsortium/itkwidgets](https://github.com/InsightSoftwareConsortium/itkwidgets) ⭐ 624 | 🐛 128 | 🌐 Python | 📅 2026-03-10 -  Interactive Jupyter widgets to visualize images, point sets, and meshes in 2D and 3D. ![Python](logo/Python.svg) ![JavaScript](logo/JavaScript.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/InsightSoftwareConsortium/itkwidgets/search?l=jupyter-notebook) ⭐ 624 | 🐛 128 | 🌐 Python | 📅 2026-03-10
* [QuantStack/ipygany](https://github.com/QuantStack/ipygany) ⭐ 494 | 🐛 43 | 🌐 Python | 📅 2023-07-20 - 3-D Scientific Visualization in the Jupyter Notebook. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/QuantStack/ipygany/search?l=jupyter-notebook) ⭐ 494 | 🐛 43 | 🌐 Python | 📅 2023-07-20
* [sciapp/gr](https://github.com/sciapp/gr) ⭐ 342 | 🐛 34 | 🌐 C | 📅 2026-08-24 - GR framework: a graphics library for visualisation applications. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
* [NVIDIA/ipyparaview](https://github.com/NVIDIA/ipyparaview) ⭐ 101 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2022-08-16 - iPython widget for server-side ParaView rendering in Jupyter. ![Python](logo/Python.svg) ![JavaScript](logo/JavaScript.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/NVIDIA/ipyparaview/search?l=jupyter-notebook) ⭐ 101 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2022-08-16
* [Kitware/Vtk](https://gitlab.kitware.com/vtk/vtk) - Visualization Toolkit. ![C++](logo/cpp.svg)
* [Kitware/paraview](https://www.paraview.org/) - An open-source, multi-platform data analysis and visualization application. ![Python](logo/Python.svg)

## Benchmarks and Datasets

### Datasets

* [shengzesnail/PIV\_dataset](https://github.com/shengzesnail/PIV_dataset) ⭐ 92 | 🐛 1 | 🌐 MATLAB | 📅 2020-09-09 - PIV dataset. ![MATLAB](logo/MATLAB.svg)
* [idies/pyJHTDB](https://github.com/idies/pyJHTDB) - Python wrapper for the Johns Hopkins turbulence database library. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/idies/pyJHTDB/search?l=jupyter-notebook)

### Benchmarks

* [dionhaefner/pyhpc-benchmarks](https://github.com/dionhaefner/pyhpc-benchmarks) ⭐ 336 | 🐛 6 | 🌐 Python | 📅 2024-10-08 - A suite of benchmarks for CPU and GPU performance of the most popular high-performance libraries for Python. ![Python](logo/Python.svg)
* [su2code/TestCases](https://github.com/su2code/TestCases) ⭐ 72 | 🐛 6 | 🌐 GLSL | 📅 2026-08-21 - An extensive collection of common test cases for SU2. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)

## Reproducibility

* [iterative/dvc](https://github.com/iterative/dvc) ⭐ 15,859 | 🐛 203 | 🌐 Python | 📅 2026-08-31 - Data Version Control, Git for Data & Models, ML Experiments Management. ![Python](logo/Python.svg)
* [sphinx-doc/sphinx](https://github.com/sphinx-doc/sphinx) ⭐ 8,002 | 🐛 1,429 | 🌐 Python | 📅 2026-08-31 - Sphinx is a tool that makes it easy to create intelligent and beautiful documentation for Python projects. ![Python](logo/Python.svg)

## Community

* [CFD Online Forum](https://www.cfd-online.com/Forums/) - A free community for everyone interested in Computational Fluid Dynamics.

## Related Topics

* [awesomedata/awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets) ⭐ 78,811 | 🐛 157 | 📅 2026-09-03 -  A topic-centric list of HQ open datasets. ![Awesome](logo/awesome.svg)
* [nschloe/awesome-scientific-computing](https://github.com/nschloe/awesome-scientific-computing) ⭐ 1,585 | 🐛 17 | 🌐 Python | 📅 2026-07-20 - Curated list of awesome software for numerical analysis and scientific computing. ![Awesome](logo/awesome.svg)
* [qd-cae/awesome-CAE](https://github.com/qd-cae/awesome-CAE) ⭐ 495 | 🐛 2 | 📅 2024-08-15 - A curated list of awesome CAE frameworks, libraries and software. ![Awesome](logo/awesome.svg)
* [alexlib/awesome\_piv](https://github.com/alexlib/awesome_piv) ⭐ 69 | 🐛 2 | 📅 2022-12-25 - A curated list of repositories related to PIV (particle image velocimetry). ![Awesome](logo/awesome.svg)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
