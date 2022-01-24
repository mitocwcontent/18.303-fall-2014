---
content_type: page
title: Syllabus
uid: a8c0207c-5cd1-77e3-3b06-7627e7904576
---

Course Meeting Times
--------------------

Lectures: 3 sessions / week, 1 hour / session

Prerequisites
-------------

[_18.06 Linear Algebra_](/courses/18-06-linear-algebra-spring-2010), [_18.700 Linear Algebra_](/courses/18-700-linear-algebra-fall-2013) or equivalent.

Description
-----------

This course provides students with the basic analytical and computational tools of linear partial differential equations (PDEs) for practical applications in science engineering, including heat/diffusion, wave, and Poisson equations.

Analytics emphasize the viewpoint of linear algebra and the analogy with finite matrix problems including operator adjoints and eigenproblems, series solutions, Green's functions, and separation of variables.

Numerics focus on finite-difference and finite-element techniques to reduce PDEs to matrix problems, including stability and convergence analysis and implicit/explicit time-stepping.

[Julia programming language](https://github.com/JuliaLang/julia) (a MATLAB®-like environment) is introduced and used in homework for simple examples. Julia is a high-level, high-performance dynamic language for technical computing, with syntax that is familiar to users of other technical computing environments. It provides a sophisticated compiler, distributed parallel execution, numerical accuracy, and an extensive mathematical function library.

Textbook
--------

There is no required text for this course, though the following books are recommended:

Strang, Gilbert. _Computational Science and Engineering_. Wellesley-Cambridge Press, 2007. ISBN: 9780961408817.  
(emphasizing more the numerical part of the course). More information, including online chapters, can be found on [Prof. Strang's CSE website](http://math.mit.edu/~gs/cse/).

Olver, Peter. [_Introduction to Partial Differential Equations_](https://www.amazon.com/Introduction-Differential-Equations-Undergraduate-Mathematics/dp/3319020986). Springer, 2013. ISBN: 9783319020983. \[Preview with [Google Books](http://books.google.com/books?id=aQ8JAgAAQBAJ&pg=PAfrontcover)\] (free online book)

Requirements
------------

There will be five problem sets and a mid-term exam. There is a final project instead of a final exam. Late problem sets are not accepted, however the lowest problem set score will be dropped at the end of the term.

Grading
-------

| ACTIVITIES | PERCENTAGES |
| --- | --- |
| Assignments | 45% |
| Midterm exam | 25% |
| Final project | 30% 

Calendar
--------

| SES # | TOPICS | KEY DATES |
| --- | --- | --- |
| L1 | Overview of linear PDEs and analogies with matrix algebra | &nbsp; |
| L2 | Poisson's equation and eigenfunctions in 1d: Fourier sine series | &nbsp; |
| L3 | Finite-difference methods and accuracy | &nbsp; |
| L4 | Discrete vs. continuous Laplacians: Symmetry and dot products | &nbsp; |
| Optional || {{< td-colspan 2 >}}Julia Tutorial{{< /td-colspan >}} ||
| L5 | Diagonalizability of infinite-dimensional Hermitian operators | Problem set 1 due |
| L6 | Start with a truly discrete (finite-dimensional) system, and then derive the continuum PDE model as a limit or approximation | &nbsp; |
| L7 | Start in 1d with the "Sturm-Liouville operator", generalize Sturm-Liouville operators to multiple dimensions | &nbsp; |
| L8 | Music and wave equations, Separation of variables, in time and space | Problem set 2 due |
| L9 | Separation of variables in cylindrical geometries: Bessel functions | &nbsp; |
| L10 | General Dirichlet and Neumann boundary conditions | &nbsp; |
| L11 | Multidimensional finite differences | &nbsp; |
| L12 | Kronecker products | Problem set 3 due |
| L13 | The min-max theorem | &nbsp; |
| L14 | Green's functions with Dirichlet boundaries | &nbsp; |
| L15 | Reciprocity and positivity of Green's functions | &nbsp; |
| L16 | Delta functions and distributions | &nbsp; |
| L17 | Green's function of ∇2 in 3d for infinite space, the method of images | Problem set 4 due |
| L18 | The method of images, interfaces, and surface integral equations | &nbsp; |
| L19 | Green's functions in inhomogeneous media: Integral equations and Born approximations | &nbsp; |
| L20 | Dipole sources and approximations, Overview of time-dependent problems | &nbsp; |
| L21 | Time-stepping and stability: Definitions, Lax equivalence | &nbsp; |
| L22 | Von Neumann analysis and the heat equation | Problem set 5 due |
| L23 | Algebraic properties of wave equations and unitary time evolution, Conservation of energy in a stretched string | &nbsp; |
| L24 | Staggered discretizations of wave equations | &nbsp; |
| L25 | Traveling waves: D'Alembert's solution | &nbsp; |
| L26 | Group-velocity derivation, Dispersion | &nbsp; |
| {{< td-colspan 3 >}}**Midterm Exam**{{< /td-colspan >}} |||
| L27 | Material dispersion and convolutions | &nbsp; |
| L28 | General topic of waveguides, Superposition of modes, Evanescent modes | &nbsp; |
| L29 | Waveguide modes, Reduced eigenproblem | &nbsp; |
| L30 | Guidance, reflection, and refraction at interfaces between regions with different wave speeds | &nbsp; |
| L31 | Numerical examples of total internal reflection | &nbsp; |
| L32 | Perfectly matched layers (PML) | &nbsp; |
| L33 | Perturbation theory and Hellman-Feynman theorem | &nbsp; |
| L34 | Finite element methods: Introduction | &nbsp; |
| L35 | Galerkin discretization | &nbsp; |
| L36 | Convergence proof for the finite-element method, Boundary conditions and the finite-element method | &nbsp; |
| L37 | Finite-element software | &nbsp; |
| L38 | Symmetry and linear PDEs | Final project due