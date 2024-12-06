---
title: "[4] Gu, M., He, Y., Liu, X., & Luo, Y. (2024). Ab initio uncertainty quantification in scattering analysis of microscopy. Physical Review E, 110(3), 034601. DOI: 10.1103/PhysRevE.110.034601."
collection: publications
permalink: 
excerpt: #'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-09-03
paperurl: 'https://journals.aps.org/pre/abstract/10.1103/PhysRevE.110.034601'
citation: ''
---




[PDF](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.110.034601)


## Abstract
Estimating parameters from data is a fundamental problem in physics, customarily done by minimizing a loss function between a model and observed statistics. In scattering-based analysis, it is common to work in the reciprocal space. Researchers often employ their domain expertise to select a specific range of wave vectors for analysis, a choice that can vary depending on the specific case. We introduce another paradigm that defines a probabilistic generative model from the beginning of data processing and propagates the uncertainty for parameter estimation, termed the ab initio uncertainty quantification (AIUQ). As an illustrative example, we demonstrate this approach with differential dynamic microscopy (DDM) that extracts dynamical information through minimizing a loss function for the squared differences of the Fourier-transformed intensities, at a selected range of wave vectors. We first show that the conventional way of estimation in DDM is equivalent to fitting a temporal variogram in the reciprocal space using a latent factor model as the generative model. Then we derive the maximum marginal likelihood estimator, which optimally weighs the information at all wave vectors, therefore eliminating the need to select the range of wave vectors. Furthermore, we substantially reduce the computational cost of computing the likelihood function without approximation, by utilizing the generalized Schur algorithm for Toeplitz covariances. Simulated studies of a wide range of dynamical systems validate that the AIUQ method improves estimation accuracy and enables model selection with automated analysis. The utility of AIUQ is also demonstrated by three distinct sets of experiments: first in an isotropic Newtonian fluid, pushing limits of optically dense systems compared to multiple particle tracking; next in a system undergoing a sol-gel transition, automating the determination of gelling points and critical exponent; and lastly, in discerning anisotropic diffusive behavior of colloids in a liquid crystal. These studies demonstrate that the new approach does not require manually selecting the wave vector range and enables automated analysis.
