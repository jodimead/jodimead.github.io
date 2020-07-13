---
title: "Joint inversion of full-waveform GPR and ER data. Part 1"
collection: publications
permalink: /publication/2020-01-01-Joint-inversion-of-full-waveform-GPR-and-ER-data.-Part-1
date: Accepted
venue: 'Geophysics'

---
Download [here](https://math.boisestate.edu/~mead/papers/joint.pdf)

Abstract: 
We develop an algorithm for joint inversion of full-waveform ground-penetrating radar
(GPR) and electrical resistivity (ER) data. GPR is sensitive to electrical permittivity
through reflectivity and velocity, and electrical conductivity through reflectivity and attenuation. ER is directly sensitive to electrical conductivity. The two types of data are inherently linked through Maxwell’s equations and we jointly invert them. Results show that
the two types of data work cooperatively to effectively regularize each other while honoring
the physics of the geophysical methods. We first compute sensitivity updates separately
for both the GPR and ER data using the adjoint method, and then we sum these updates
to account for both types of sensitivities. The sensitivities are added with the paradigm of
letting both data types always contribute to our inversion in proportion to how well their
respective objective functions are being resolved in each iteration. Our algorithm makes no
assumption of the subsurface geometry nor structural similarities between parameters with
the caveat of needing a good initial model. We find that our joint inversion outperforms
both GPR and ER separate inversions and determine that GPR effectively supports ER in
regions of low conductivity while ER supports GPR in regions with strong attenuation.
