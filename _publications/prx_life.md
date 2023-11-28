---
title: "[2] Gu, M., Fang, X., & Luo, Y. (2023). Data-driven model construction for anisotropic dynamics of active matter. PRX Life, 1(1), 013009."
collection: publications
permalink: 
excerpt: #'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-08-15
paperurl: 'https://journals.aps.org/prxlife/abstract/10.1103/PRXLife.1.013009'
citation: ''
---




[PDF](https://journals.aps.org/prxlife/abstract/10.1103/PRXLife.1.013009)
[Code](https://github.com/UncertaintyQuantification/data_driven_cell_model)


## Abstract
The dynamics of cellular pattern formation is crucial for understanding embryonic development and tissue morphogenesis. Recent studies have shown that human dermal fibroblasts cultured on liquid crystal elastomers can exhibit an increase in orientational alignment over time, accompanied by cell proliferation, under the influence of the weak guidance of a molecularly aligned substrate. However, a comprehensive understanding of how this order arises remains largely unknown. This knowledge gap may be attributed, in part, to a scarcity of mechanistic models that can capture the temporal progression of the complex nonequilibrium dynamics during the cellular alignment process. The orientational alignment occurs primarily when cells reach a high density near confluence. Therefore, for accurate modeling, it is crucial to take into account both the cell-cell interaction term and the influence from the substrate, acting as a one-body external potential term. To fill in this gap, we develop a hybrid procedure that utilizes statistical learning approaches to extend the state-of-the-art physics models for quantifying both effects. We develop a more efficient way to perform feature selection that avoids testing all feature combinations through simulation. The maximum likelihood estimator of the model was derived and implemented in computationally scalable algorithms for model calibration and simulation. By including these features, such as the non-Gaussian, anisotropic fluctuations, and limiting alignment interaction only to neighboring cells with the same velocity direction, this model quantitatively reproduce the key system-level parameters—the temporal progression of the velocity orientational order parameters and the variability of velocity vectors—whereas models missing any of the features fail to capture these temporally dependent parameters. The computational tools we develop for automating model construction and calibration can be applied to other systems of active matter.
