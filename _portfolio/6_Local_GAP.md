---
title: "Refined Gap Safe Screening"
excerpt: "GAP Safe Screening with local regularity assumptions, applied to beta-divergences. (MATLAB)<br/><img src='/images/500x300.png'>"
collection: portfolio
code: 'https://github.com/cassiofragadantas/KL_screening'
---

This work extends the existing Gap Safe[^1] screening framework 
by relaxing global regularity assumptions to their local counterpart.
<!--
by relaxing the global strong-concavity assumption on the dual cost function. 
Instead, we exploit local regularity properties, that is, strong concavity on 
well-chosen subsets of the domain. The non-negativity constraint is also
integrated to the existing framework.
-->
Besides making safe screening possible to a broader class of functions which includes beta-divergences (e.g., the Kullback-Leibler divergence), 
the proposed approach also improves upon the existing Gap Safe screening rules on previously applicable cases (e.g., logistic regression).

This code corresponds to the following papers:

> C.F. Dantas, E. Soubies, C. Févotte, "Expanding boundaries of Gap Safe screening." Pre-print, 2021.

> C.F. Dantas, E. Soubies, C. Févotte, "Safe screening for sparse regression with the Kullback-Leibler divergence." In ICASSP, 2021.

Related slides [here](https://www.dropbox.com/sh/5f1qnrk3gu9asg6/AABv5uZ5lasmcnLASuGwpVM4a?preview=2021-04_Expanding-GAP_ML-MTP_CFDantas.pdf)
and [here](https://www.dropbox.com/sh/5f1qnrk3gu9asg6/AABv5uZ5lasmcnLASuGwpVM4a?preview=2021-06_KL-Screening_ICASSP_CFDantas.pdf)

<img src='/images/portfolio/2021_RefinedGAP.gif'>

The strong concavity bound $\alpha$ is iteratively refined within the current GAP Safe sphere $\mathcal{B}(\theta,r)$.

[^1]: E. Ndiaye, O. Fercoq, A. Gramfort, and J. Salmon. "Gap safe screening rules for sparsity enforcing penalties." JMLR, 2017.

