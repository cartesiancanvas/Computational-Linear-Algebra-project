# Computational-Linear-Algebra-Course project
Arnoldi Iteration: Krylov Subspaces, GMRES and Ritz Value Approximation
This report studies the Arnoldi iteration and its connection
with Krylov subspaces, eigenvalue approximation and the
Generalized Minimal Residual (GMRES) method. We first
develop the Arnoldi process and interpret it as an orthogonal
projection of a linear operator onto a Krylov subspace.
We then examine how the eigenvalues of the resulting
Hessenberg matrix, known as Ritz values, approximate the
eigenvalues of the original matrix. The Ritz residual and
the Galerkin condition are used to understand the quality
of these approximations, with particular attention to the
difference between normal and nonnormal matrices.

The report also develops GMRES from its least-squares
formulation and studies its interpretation as a polynomial
minimisation problem. This viewpoint helps explain how the
location of eigenvalues can influence convergence, and
why eigenvalues alone may not fully describe the behaviour
of GMRES for nonnormal matrices. Numerical experiments
illustrate these ideas through comparisons of normal and
nonnormal matrices, as well as matrices with disk-shaped
and rose-shaped eigenvalue distributions. These examples
provide a computational perspective on the theoretical
properties of Arnoldi iteration and GMRES.
