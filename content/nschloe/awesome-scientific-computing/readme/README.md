# Awesome Scientific Computing Overview

:sunglasses: Curated list of awesome software for numerical analysis and scientific computing

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/nschloe/awesome-scientific-computing/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 nschloe/awesome-scientific-computing](https://github.com/nschloe/awesome-scientific-computing) · ⭐ 1.3K · 🏷️ Miscellaneous

[ [Daily](/content/nschloe/awesome-scientific-computing/README.md) / [Weekly](/content/nschloe/awesome-scientific-computing/week/README.md) / Overview ]

---

# Awesome Scientific Computing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://nschloe.github.io/awesome-scientific-computing/sunglasses.svg" align="right" width="30%">](#readme)

> Useful resources for scientific computing and numerical analysis.

Scientific computing and numerical analysis are research fields that aim to provide
methods for solving large-scale problems from various areas of science with the help of
computers. Typical problems are ordinary and partial differential equations (ODEs,
PDEs), their discretizations, and the solution of linear algebra problems arising from
them.

## Contents

*   [Basic linear algebra](#basic-linear-algebra)
*   [Multi-purpose toolkits](#multi-purpose-toolkits)
*   [Finite Elements](#finite-elements)
*   [Meshing](#meshing)
*   [Data formats](#data-formats)
*   [Sparse linear solvers](#sparse-linear-solvers)
*   [Visualization](#visualization)
*   [Other libraries and tools](#other-libraries-and-tools)
*   [Community](#community)

## Basic linear algebra

*   [BLAS](https://netlib.org/blas/) - Standard building blocks for performing basic vector and matrix operations.
    (Fortran, public domain, [GitHub (⭐1.5k)](https://github.com/Reference-LAPACK/lapack/tree/master/BLAS))
*   [OpenBLAS](https://www.openblas.net) - Optimized BLAS library based on GotoBLAS2.
    (C and Assembly, BSD, [GitHub (⭐6.4k)](https://github.com/OpenMathLib/OpenBLAS))
*   [BLIS (⭐2.3k)](https://github.com/flame/blis) - High-performance BLAS-like dense linear algebra libraries.
    (C, BSD, GitHub)
*   [LAPACK](https://netlib.org/lapack/) - Routines for solving systems of linear equations, linear least-squares, eigenvalue problems, etc.
    (Fortran, BSD, [GitHub (⭐1.5k)](https://github.com/Reference-LAPACK/lapack))
*   [Eigen](https://eigen.tuxfamily.org/index.php?title=Main_Page) - C++ template library for linear algebra.
    (C++, MPL 2, [GitLab](https://gitlab.com/libeigen/eigen))
*   [Ginkgo](https://ginkgo-project.github.io/) - High-performance manycore linear algebra library, focus on sparse systems.
    (C++, BSD, [GitHub (⭐415)](https://github.com/ginkgo-project/ginkgo))
*   [blaze](https://bitbucket.org/blaze-lib/blaze) - High-performance C++ math library for dense and sparse arithmetic.
    (C++, BSD, Bitbucket)

## Multi-purpose toolkits

*   [PETSc](https://www.mcs.anl.gov/petsc/) - Parallel solution of scientific applications modeled by PDEs.
    (C, 2-clause BSD, [GitLab](https://gitlab.com/petsc/petsc))
*   [DUNE Numerics](https://www.dune-project.org) - Toolbox for solving PDEs with grid-based methods.
    (C++, GPL 2, [GitLab](https://gitlab.dune-project.org/core/))
*   [SciPy](https://scipy.org) - Python modules for statistics, optimization, integration, linear algebra, etc.
    (Python, mostly BSD, [GitHub (⭐13k)](https://github.com/scipy/scipy/))
*   [NumPy](https://numpy.org/) - Fundamental package needed for scientific computing with Python.
    (Python, BSD, [GitHub (⭐28k)](https://github.com/numpy/numpy))
*   [DifferentialEquations.jl](https://diffeq.sciml.ai/) - Toolbox for solving different types of differential equations numerically. (Julia, MIT, [GitHub (⭐2.9k)](https://github.com/SciML/DifferentialEquations.jl))

## Finite Elements

*   [FEniCS](https://fenicsproject.org) - Computing platform for solving PDEs in Python and C++.
    (C++/Python, LGPL 3, [GitHub](https://github.com/FEniCS)/[Bitbucket](https://bitbucket.org/fenics-project/))
*   [libMesh](https://libmesh.github.io) - Framework for the numerical simulation of PDEs using unstructured discretizations.
    (C++, LGPL 2.1, [GitHub (⭐660)](https://github.com/libMesh/libmesh))
*   [deal.II](https://dealii.org) - Software library supporting the creation of finite element codes.
    (C++, LGPL 2.1, [GitHub (⭐1.4k)](https://github.com/dealii/dealii))
*   [Netgen/NGSolve](https://ngsolve.org) - High performance multiphysics finite element software.
    (C++, LGPL 2.1, [GitHub (⭐302)](https://github.com/NGSolve/netgen))
*   [Firedrake](https://www.firedrakeproject.org) - Automated system for the solution of PDEs using the finite element method.
    (Python, LGPL 3, [GitHub (⭐521)](https://github.com/firedrakeproject/firedrake))
*   [MOOSE](https://mooseframework.inl.gov/) - Multiphysics Object Oriented Simulation Environment.
    (C++, LGPL 2.1, [GitHub (⭐1.8k)](https://github.com/idaholab/moose))
*   [MFEM](https://mfem.org) - Free, lightweight, scalable C++ library for finite element methods.
    (C++, BSD-3-Clause, [GitHub (⭐1.7k)](https://github.com/mfem/mfem))
*   [SfePy](https://sfepy.org) - Simple Finite Elements in Python.
    (Python, BSD, [GitHub (⭐751)](https://github.com/sfepy/sfepy))
*   [FreeFEM](https://freefem.org) - High level multiphysics-multimesh finite element language.
    (C++, LGPL, [GitHub](https://github.com/FreeFem))
*   [libceed](https://libceed.readthedocs.io/en/latest/index.html) - Code for Efficient Extensible Discretizations.
    (C, 2-clause BSD, [GitHub (⭐205)](https://github.com/CEED/libCEED))
*   [scikit-fem (⭐513)](https://github.com/kinnala/scikit-fem) - Simple finite element assemblers.
    (Python, BSD/GPL, GitHub)

## Meshing

### Triangular and tetrahedral meshing

*   [Gmsh](https://gmsh.info) - Three-dimensional finite element mesh generator with pre- and post-processing facilities.
    (C++, GPL, [GitLab](https://gitlab.onelab.info/gmsh/gmsh))
*   [pygmsh (⭐865)](https://github.com/nschloe/pygmsh) - Python interface for Gmsh.
    (Python, GPL 3, GitHub)
*   [MeshPy](https://mathema.tician.de/software/meshpy/) - Quality triangular and tetrahedral mesh generation.
    (Python, MIT, [GitHub (⭐522)](https://github.com/inducer/meshpy))
*   [CGAL](https://www.cgal.org) - Algorithms for computational geometry.
    (C++, mixed LGPL/GPL, [GitHub (⭐5k)](https://github.com/CGAL/cgal))
*   [pygalmesh (⭐600)](https://github.com/meshpro/pygalmesh) - Python interface for CGAL's 3D meshing capabilities.
    (Python, GPL 3, GitHub)
*   [TetGen](https://www.wias-berlin.de/software/index.jsp?id=TetGen) - Quality tetrahedral mesh generator and 3D Delaunay triangulator.
    (C++, AGPLv3)
*   [Triangle](https://www.cs.cmu.edu/~quake/triangle.html) - Two-dimensional quality mesh generator and Delaunay triangulator.
    (C, *nonfree software*)
*   [distmesh](http://persson.berkeley.edu/distmesh/) - Simple generator for unstructured triangular and tetrahedral meshes.
    (MATLAB, GPL 3)
*   [trimesh](https://trimesh.org) - Loading and using triangular meshes with an emphasis on watertight surfaces.
    (Python, MIT, [GitHub (⭐3k)](https://github.com/mikedh/trimesh))
*   [dmsh (⭐210)](https://github.com/meshpro/dmsh) - Simple generator for unstructured triangular meshes, inspired by distmesh.
    (Python, proprietary, GitHub)
*   [TetWild](https://yixin-hu.github.io/tetwild.pdf) - Generate tetrahedral meshes for triangular surface meshes.
    (C++, GPL 3, [GitHub (⭐619)](https://github.com/Yixin-Hu/TetWild))
*   [TriWild](https://cims.nyu.edu/gcl/papers/2019-TriWild.pdf) - Robust triangulation with curve constraints.
    (C++, MPL 2, [GitHub (⭐235)](https://github.com/wildmeshing/TriWild))
*   [fTetWild](https://arxiv.org/abs/1908.03581) - Same as TetWild, but faster.
    (C++, MPL 2, [GitHub (⭐425)](https://github.com/wildmeshing/fTetWild))
*   [SeismicMesh (⭐129)](https://github.com/krober10nd/SeismicMesh) - Parallel 2D/3D triangle/tetrahedral mesh generation with sliver removal.
    (Python and C++, GPL 3, GitHub)

### Quadrilateral and hexahedral meshing

*   [QuadriFlow](https://stanford.edu/~jingweih/papers/quadriflow/) - Scalable and robust quadrangulation from triangulation.
    (C++, BSD, [GitHub (⭐677)](https://github.com/hjwdzh/QuadriFlow))

### Mesh tools

*   [meshio (⭐2k)](https://github.com/nschloe/meshio) - I/O for various mesh formats, file conversion.
    (Python, MIT, GitHub)
*   [MOAB](https://sigma.mcs.anl.gov/moab-library/) - Representing and evaluating mesh data.
    (C++, mostly LGPL 3, [Bitbucket](https://bitbucket.org/fathomteam/moab/))
*   [optimesh (⭐580)](https://github.com/meshpro/optimesh) - Triangular mesh smoothing.
    (Python, proprietary, GitHub)
*   [pmp-library](https://www.pmp-library.org/) - Polygon mesh processing library.
    (C++, MIT with Employer Disclaimer, [GitHub (⭐1.3k)](https://github.com/pmp-library/pmp-library/))
*   [Mmg](https://www.mmgtools.org/) - Robust, open-source & multidisciplinary software for remeshing.
    (C, LGPL 3, [GitHub (⭐375)](https://github.com/MmgTools/mmg))
*   [meshplex (⭐104)](https://github.com/meshpro/meshplex) - Fast tools for simplex meshes.
    (Python, proprietary, GitHub)

## Data formats

*   [NetCDF](https://www.unidata.ucar.edu/software/netcdf/) - Software libraries and data formats for array-oriented scientific data.
    (C/C++/Fortran/Java/Python, [custom open-source
    license](https://www.unidata.ucar.edu/software/netcdf/copyright.html),
    [GitHub (⭐520)](https://github.com/Unidata/netcdf-c/))
*   [HDF5](https://www.hdfgroup.org/solutions/hdf5/) - Data model, library, and file format for storing and managing data.
    (C/Fortran, BSD, [GitHub (⭐637)](https://github.com/HDFGroup/hdf5))
*   [XDMF](https://xdmf.org/index.php/Main_Page) - eXtensible Data Model and Format for data from High Performance Computing codes.
    (C++, [GitLab](https://gitlab.kitware.com/xdmf/xdmf))
*   [Zarr](https://zarr.readthedocs.io/en/stable/) - Format for the storage of chunked, compressed, N-dimensional arrays.
    (Python, MIT, [GitHub (⭐1.5k)](https://github.com/zarr-developers/zarr-python))

## Sparse linear solvers

*   [SuperLU](https://portal.nersc.gov/project/sparse/superlu/) - Direct solution of large, sparse, nonsymmetric systems of linear equations.
    (C, mostly BSD, [GitHub (⭐281)](https://github.com/xiaoyeli/superlu))
*   [PyAMG](https://pyamg.readthedocs.io/en/latest/) - Algebraic Multigrid Solvers in Python.
    (Python, MIT, [GitHub (⭐575)](https://github.com/pyamg/pyamg))
*   [hypre](https://computing.llnl.gov/projects/hypre-scalable-linear-solvers-multigrid-methods) - Library of high-performance preconditioners and solvers.
    (C, Apache 2.0/MIT, [GitHub (⭐713)](https://github.com/hypre-space/hypre))

## Visualization

*   [ParaView](https://www.paraview.org) - Multi-platform data analysis and visualization application based on VTK.
    (C++, BSD, [GitLab](https://gitlab.kitware.com/paraview/paraview))
*   [VTK](https://vtk.org/) - Process images and create 3D computer graphics.
    (C++, BSD, [GitLab](https://gitlab.kitware.com/vtk/vtk))
*   [Mayavi](https://docs.enthought.com/mayavi/mayavi/) - 3D scientific data visualization and plotting in Python.
    (Python, BSD, [GitHub (⭐1.3k)](https://github.com/enthought/mayavi))
*   [Polyscope](https://polyscope.run/) - Viewer and user interface for 3D geometry processing.
    (C++, MIT, [GitHub (⭐1.8k)](https://github.com/nmwsharp/polyscope))
*   [PyVista](https://docs.pyvista.org/) - 3D plotting and mesh analysis through a streamlined interface for VTK.
    (Python, MIT, [GitHub (⭐2.8k)](https://github.com/pyvista/pyvista))
*   [vedo](https://vedo.embl.es) - Library for scientific analysis and visualization of 3D objects based on VTK.
    (Python, MIT, [GitHub (⭐2.1k)](https://github.com/marcomusy/vedo))
*   [yt](https://yt-project.org/) - Toolkit for analysis and visualization of volumetric data.
    (Python, BSD, [GitHub (⭐469)](https://github.com/yt-project/yt))
*   [F3D](https://f3d.app/) - Cross-platform, fast, and minimalist 3D viewer with scientific visualization tools.
    (C++, BSD, [GitHub (⭐2.9k)](https://github.com/f3d-app/f3d))
*   [TTK](https://topology-tool-kit.github.io/) - Topological data analysis and visualization.
    (C++/Python, BSD, [GitHub (⭐423)](https://github.com/topology-tool-kit/ttk))
*   [morphologica (⭐260)](https://github.com/ABRG-Models/morphologica) - Header-only, modern OpenGL code to visualize numerical simulations at runtime. (C++, Apache 2.0, GitHub)

## Other libraries and tools

*   [FFTW](http://www.fftw.org) - Discrete Fourier transforms in one or more dimensions, of arbitrary input size, real and complex.
    (C, GPL2, [GitHub (⭐2.8k)](https://github.com/FFTW/fftw3))
*   [Qhull](http://www.qhull.org) - Convex hull, Delaunay triangulation, Voronoi diagram, halfspace intersection about a point, etc.
    (C/C++, [custom open source license](http://www.qhull.org/COPYING.txt),
    [GitHub (⭐738)](https://github.com/qhull/qhull/))
*   [GSL](https://www.gnu.org/software/gsl/) - Random number generators, special functions, and least-squares fitting etc.
    (C/C++, GPL 3, [Savannah](https://savannah.gnu.org/projects/gsl))
*   [OpenFOAM](https://www.openfoam.com) - Free, open source CFD (computational fluid dynamics) software.
    (C++, GPL 3, [GitHub (⭐1.6k)](https://github.com/OpenFOAM/OpenFOAM-dev))
*   [quadpy (⭐765)](https://github.com/sigma-py/quadpy) - Numerical integration (quadrature, cubature) in Python.
    (Python, proprietary, GitHub)
*   [FiPy](https://www.ctcms.nist.gov/fipy/) - Finite-volume PDE solver.
    (Python, [custom open-source
    license](https://www.nist.gov/open/copyright-fair-use-and-licensing-statements-srd-data-software-and-technical-series-publications),
    [GitHub (⭐517)](https://github.com/usnistgov/fipy))
*   [accupy (⭐104)](https://github.com/sigma-py/accupy) - Accurate sums and dot products for Python.
    (Python, GPL 3, GitHub)
*   [SLEPc](https://slepc.upv.es) - Scalable Library for Eigenvalue Problem Computations.
    (C, 2-clause BSD, [GitLab](https://gitlab.com/slepc/slepc))
*   [Chebfun](https://www.chebfun.org/) - Computing with functions to about 15-digit accuracy.
    (MATLAB, BSD, [GitHub (⭐614)](https://github.com/chebfun/chebfun))
*   [pyMOR](https://pymor.org/) - Model Order Reduction with Python.
    (Python, 2-clause BSD, [GitHub (⭐310)](https://github.com/pymor/pymor/))
*   [cvxpy](https://www.cvxpy.org/) - Modeling language for convex optimization problems.
    (Python, Apache 2.0, [GitHub (⭐5.5k)](https://github.com/cvxpy/cvxpy))
*   [PyWavelets](https://pywavelets.readthedocs.io/en/latest/) - Wavelet transforms in Python.
    (Python, MIT, [GitHub (⭐2.1k)](https://github.com/PyWavelets/pywt))
*   [NFFT](https://www-user.tu-chemnitz.de/~potts/nfft/) - Nonequispaced fast Fourier transform.
    (C/MATLAB, GPL 2, [GitHub (⭐175)](https://github.com/NFFT/nfft))
*   [preCICE](https://precice.org/) - Coupling library for partitioned multi-physics simulations (FSI, CHT, and more).
    (C++, LGPL 3, [GitHub](https://github.com/precice/))
*   [orthopy (⭐182)](https://github.com/sigma-py/orthopy) - Compute orthogonal polynomials efficiently.
    (Python, proprietary, GitHub)
*   [pyGAM](https://pygam.readthedocs.io/en/latest/) - Generalized Additive Models in Python.
    (Python, Apache 2.0, [GitHub (⭐877)](https://github.com/dswah/pyGAM))
*   [Dedalus](https://dedalus-project.org/) - Solve partial differential equations with spectral methods.
    (Python, GPL 3, [GitHub (⭐524)](https://github.com/DedalusProject/dedalus))
*   [PyGMO](https://esa.github.io/pygmo/) - Massively parallel optimization.
    (Python/C++, MPL 2, [GitHub (⭐453)](https://github.com/esa/pygmo2))
*   [shenfun](https://shenfun.readthedocs.io/en/latest/) - High-performance Python library for the spectral Galerkin method.
    (Python, BSD-2, [GitHub (⭐204)](https://github.com/spectralDNS/shenfun))
*   [PyDMD (⭐77)](https://github.com/mathLab/PyDMD) - Dynamic Mode Decomposition (DMD) in Python.
    (Python, MIT, GitHub)
*   [HPDDM (⭐140)](https://github.com/hpddm/hpddm) - High-performance unified framework for domain decomposition methods.
    (C++, LGPL 3, GitHub)

## Community

*   [SciComp StackExchange](https://scicomp.stackexchange.com/) - Computational Science on the StackExchange network.
*   [Wolfgang Bangerth's video class](https://www.math.colostate.edu/~bangerth/videos.html) - MATH 676: Finite element methods in scientific computing.
*   [Nick Higham's blog](https://nhigham.com/) - Mostly on MATLAB, general computing advice.
*   [Nick Trefethen's Video Lectures](https://people.maths.ox.ac.uk/trefethen/videos.html) - 36 video lectures on approximation theory/practice and scientific computing.
*   [John D. Cook's blog](https://www.johndcook.com/blog/) - Feats of scientific computing.
*   [Jack Dongarra's software list](https://netlib.org/utk/people/JackDongarra/la-sw.html) - List of freely available software for the solution of linear algebra problems.
*   [NA Digest](https://netlib.org/na-digest-html/) - Collection of articles on topics related to numerical analysis and those who practice it.
*   [Gabriel Peyré on Bluesky](https://bsky.app/profile/gabrielpeyre.bsky.social) - One post a day on computational mathematics.
*   [Discord: Numerical Software](https://discord.com/invite/hnTJ5MRX2Y) - Discord messaging server on numerical software.

