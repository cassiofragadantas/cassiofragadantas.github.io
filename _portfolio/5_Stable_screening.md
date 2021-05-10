---
title: "Stable Safe Screening"
excerpt: " Safe screening rules for sparse regression with approximate dictionaries. (Python)<br/><img src='/images/500x300.png'>"
collection: portfolio
code: 'https://github.com/cassiofragadantas/Screening_ADST'
---

A dynamic safe screening approach which is robust to approximation errors on the dictionary matrix.
This allows, for instance, to combine safe screening with the use of fast structured dictionaries for accelerating the solution of sparse regression problems.

This code corresponds to the following papers:

> C. F. Dantas and R. Gribonval, "Stable safe screening and structured dictionaries for faster L1 regularization." In IEEE Transactions on Signal Processing (Apr 2019).

> C. F. Dantas and R. Gribonval, “Faster and still safe: combining screening techniques and structured dictionaries to accelerate the lasso.” In ICASSP (Apr 2018).

> C. F. Dantas and R. Gribonval, “Dynamic screening with approximate dictionaries.” In Colloque GRETSI (Sep 2017).


Related slides [here](https://www.dropbox.com/sh/5f1qnrk3gu9asg6/AABv5uZ5lasmcnLASuGwpVM4a?preview=2018_Screening_ICASSP.pdf),
[here](https://www.dropbox.com/sh/5f1qnrk3gu9asg6/AABv5uZ5lasmcnLASuGwpVM4a?preview=2017_Screening_GRETSI.pdf)
and [here](https://www.dropbox.com/sh/5f1qnrk3gu9asg6/AABv5uZ5lasmcnLASuGwpVM4a?preview=2019_PhD_Thesis_Defense.pdf) (until slide 30).

<img src='/images/portfolio/2018_Stable_Screening1.png'>

$\mathbf{\tilde{D}}$ is a fast structured approximation of $\mathbf{D}$.

The initial iterations with the approximate dictionary are much faster. To ensure convergence, the true dictionary takes over at some point.

<img src='/images/portfolio/2018_Stable_Screening2.png'>

