---
title: "Efficient inversion of 2.5D electrical resistivity data using the discrete adjoint method"
collection: publications
permalink: /publication/2021-2-01-Efficient-inversion-of-25D-electrical-resistivity-data-using-the-discrete-adjoint-method
date: 2021-02-01
venue: 'Geophysics'
---

Download [here](https://jodimead.github.io/files/papers/ER-25D.pdf)

Abstract: 
We present a memory and operation-count efficient 2.5D inversion algorithm of electrical
resistivity (ER) data that can handle fine discretization domains imposed by other geophysical (e.g, ground penetrating radar or seismic) data. Due to numerical stability criteria and
available computational memory, joint inversion of different types of geophysical data can
impose different grid discretization constraints on the model parameters. Our algorithm
enables the ER data sensitivities to be directly joined with other geophysical data without
the need of interpolating or coarsening the discretization. We employ the adjoint method
directly in the discretized Maxwell’s steady state equation in order to compute the data
sensitivity to the conductivity. In doing so, we make no finite difference approximation on
the Jacobian of the data and avoid the need to store large and dense matrices. Rather,
we exploit matrix-vector multiplication of sparse matrices and find successful convergence
using gradient descent for our inversion routine without having to resort to the Hessian
of the objective function. By assuming a 2.5D subsurface, we are able to linearly reduce
memory requirements when compared to a 3D gradient descent inversion, and by a power
of two when compared to storing a 2D Hessian. Moreover, our method linearly outperforms
operation counts when compared to 3D Gauss-Newton conjugate-gradient schemes, which 
scales cubically in our favor with respect to the thickness of the 3D domain. We physically
appraise the domain of the recovered conductivity using a cut-off of the electric current
density present in our survey. We present two case studies in order to assess the validity
of our algorithm. First, on a 2.5D synthetic example, and then on field data acquired in a
controlled alluvial aquifer, where we were able match the recovered conductivity to borehole
observations

Bibtex:<br>
@article{Domenzain_ER25D,<br>
&nbsp;  year = 2021,<br>
&nbsp;   month = {feb},<br>
&nbsp;  publisher = {Society of Exploration Geophysicists (SEG)},<br>
&nbsp;  volume = {86},<br>
&nbsp;  number = {3},<br>
&nbsp;  pages = {1--54},<br>
&nbsp; author = {Diego Domenzain and John Bradford and Jodi Mead},<br>
&nbsp; title = {Efficient inversion of 2.5 D electrical resistivity data using the discrete adjoint method},<br>
&nbsp;  journal = {GEOPHYSICS}<br>
}
