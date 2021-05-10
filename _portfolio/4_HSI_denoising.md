---
title: "Hyperspectral Image Denoising with Dictionary Learning"
excerpt: "Plug-and-play hyperspectral image denoising tool combining low-rank and sparsity priors. (MATLAB)<br/><img src='/images/500x300.png'>"
collection: portfolio
code: 'https://github.com/cassiofragadantas/Hyperspectral_Image_Denoising_DL'
---
Plug-and-play hyperspectral image denoising tool combining low-rank and sparsity priors.

This code corresponds to the following paper:

> C.F. Dantas, J.E. Cohen, and R. Gribonval. "Hyperspectral Image Denoising using Dictionary Learning." In WHISPERS, 2019.

Related slides [here](https://www.dropbox.com/sh/5f1qnrk3gu9asg6/AABv5uZ5lasmcnLASuGwpVM4a?preview=2019_HO-SuKro_Whispers.pdf).

The hyperspectral image cube is matricized (by vectorizing the two spatial dimensions at each spectral band).
and later approximated in a **low-rank** model.

<img src='/images/portfolio/2019_HSIdenoising1.png'>

Each of the eigen-images (columns of the left SVD factor) is then used to learn a dictionary in a patch-based fashion.
Finally, the learned dictionary is used to **sparsely** reconstruct the input image.

<img src='/images/portfolio/2019_HSIdenoising2.png'>
