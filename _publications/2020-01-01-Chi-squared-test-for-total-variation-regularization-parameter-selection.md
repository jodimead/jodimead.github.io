---
title: "Chi-squared test for total variation regularization parameter selection"
collection: publications
permalink: /publication/2020-01-01-Chi-squared-test-for-total-variation-regularization-parameter-selection
date: 2020-01-01
venue: 'Inverse Problems &amp; Imaging'

---
Download [here](https://math.boisestate.edu/~mead/papers/TV.pdf)

Abstract: 
Total Variation (TV) is an effective method of removing noise in
digital image processing while preserving edges. The scaling or regularization
parameter in the TV process defines the amount of denoising, with a value of
zero giving a result equivalent to the input signal. The discrepancy principle is
a classical method for regularization parameter selection whereby data is fit to
a specified tolerance. The tolerance is often identified based on the fact that
the least squares data fit is known to follow a χ^2 distribution. However, this
approach fails when the number of parameters is greater than or equal to the
number of data. Typically, heuristics are employed to identify the tolerance
in the discrepancy principle and this leads to oversmoothing. In this work
we identify a χ^2
test for TV regularization parameter selection assuming the
blurring matrix is full rank. In particular, we prove that the degrees of freedom
in the TV regularized residual is the number of data and this is used to identify
the appropriate tolerance. The importance of this work lies in the fact that
the χ^2
test introduced here for TV automates the choice of regularization
parameter selection and can straightforwardly be incorporated into any TV
algorithm. Results are given for three test images and compared to results
using the discrepancy principle and MAP estimates.
