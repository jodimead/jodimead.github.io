---
title: "Regularization parameter estimation for large-scale Tikhonov regularization using a priori information"
collection: publications
permalink: /publication/2010-01-01-Regularization-parameter-estimation-for-large-scale-Tikhonov-regularization-using-a-priori-information
date: 2010-01-01
venue: 'Computational Statistics and Data Analysis'

---
Download [here](https://math.boisestate.edu/~mead/papers/paper04.pdf)

Abstract: 
This paper is concerned with estimating the solutions of numerically ill-posed least squares problems
through Tikhonov regularization. Given a priori estimates on the covariance structure of errors in the measurement
data b, and a suitable statistically-chosen σ, the Tikhonov regularized least squares functional J(σ) = ||Ax −b||^2_Wb+ 1/σ^2||D(x − x0)||^2_2, evaluated at its minimizer x(σ), approximately follows a χ^2 distribution with m˜ degrees of freedom. Here m˜ = m + p − n for A ∈ R^(m×n), D ∈ R^(p×n), matrix Wb is the inverse covariance
matrix of the mean 0 normally distributed measurement errors e in b, and x0 is an estimate of the mean value of
x. Using the generalized singular value decomposition of the matrix pair [W^1/2_b AD], σ can then be found such
that the resulting J follows this χ^2 distribution, Mead and Renaut (2008). Because the algorithm explicitly relies on
the direct solution of the problem obtained using the generalized singular value decomposition it is not practical for
large scale problems. Here the approach is extended for large scale problems through the use of the Newton iteration
in combination with a Golub-Kahan iterative bidiagonalization of the regularized problem. The algorithm is also
extended for cases in which x0 is not available, but instead a set of measurement data provides an estimate of the
mean value of b. The sensitivity of the Newton algorithm to the number of steps used in the Golub-Kahan iterative
bidiagonalization, and the relation between the size of the projected subproblem and σ are discussed. Experiments
presented contrast the efficiency and robustness with other standard methods for finding the regularization parameter
for a set of test problems and for the restoration of a relatively large real seismic signal. An application for image
deblurring also validates the approach for large scale problems. We conclude that the presented approach is robust
for both small and large scale discretely ill-posed least squares problems.

Bibtex:<br>
@article{Renaut_etal_2010,<br>
&nbsp;  title = {Regularization parameter estimation for large-scale Tikhonov regularization using a priori information},<br>
&nbsp;  journal = {Computational Statistics and Data Analysis},<br>
&nbsp;  year = {2010},<br>
&nbsp;  volume = {54},<br>
&nbsp;  number = {12},<br>
&nbsp;  pages = {3430-3445},<br>
&nbsp;  author = {Renaut, R.A. and Hnetynkova, I. and Mead, J.}<br>}
