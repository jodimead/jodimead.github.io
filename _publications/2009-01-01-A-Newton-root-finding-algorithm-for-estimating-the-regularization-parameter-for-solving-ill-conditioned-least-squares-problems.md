---
title: "A Newton root-finding algorithm for estimating the regularization parameter for solving ill-conditioned least squares problems"
collection: publications
permalink: /publication/2009-01-01-A-Newton-root-finding-algorithm-for-estimating-the-regularization-parameter-for-solving-ill-conditioned-least-squares-problems
date: 2009-01-01
venue: 'Inverse Problems'

---
Download [here](https://jodimead.github.io/files/papers/meadrenaut_submit.pdf)

Abstract: 
We discuss the solution of numerically ill-posed overdetermined systems of equations using Tikhonov a-priori-based regularization. When the noise distribution on the measured data is available to appropriately weight the fidelity term, and the regularization is assumed to be weighted by inverse covariance information on the model parameters, the underlying cost functional becomes a random variable that follows a χ^2 distribution. The regularization parameter be then be found so that the optimal cost functional has this property. Under
this premise a scalar Newton root-finding algorithm for obtaining the regularization parameter
is presented. The algorithm, which uses the singular value decomposition of the system matrix
is found to be very efficient for parameter estimation, requiring on average about 10 Newton
steps. Additionally, the theory and algorithm apply for Generalized Tikhonov regularization
using the generalized singular value decomposition. The performance of the Newton algorithm
is contrasted with standard techniques, including the L-curve, generalized cross validation and
unbiased predictive risk estimation. This χ^2-curve Newton method of parameter estimation is
seen to be robust and cost effective in comparison to other methods, when white or colored
noise information on the measured data is incorporated.

Bibtex:<br>
@article{Mead_Renaut_2009,<br>
&nbsp;  title = {A Newton root-finding algorithm for estimating the regularization parameter for solving ill-conditioned least squares problems},<br>
&nbsp;  journal = {Inverse Problems},<br>
&nbsp;  year = {2009},volume = {25},number = {2},<br>
&nbsp;  author = {Mead, J.L. and Renaut, R.A.}<br>}
