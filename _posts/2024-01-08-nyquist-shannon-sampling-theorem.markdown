---
layout: post
title:  "The Nyquist-Shannon Sampling Theorem"
date:   2024-01-08
categories: nyquist shannon sampling theorem
---
- Why should we care about the sampling theorem and what does it say in nontechnical terms?
- - important when reconstructing a signal from finite samples 
- - aliasing is the poster child for this theorem. What about uncertainty principle?
- How does this reconstruction happen? Can do this based on the frequency spectrum of the sampled data.
- preliminaries: types of Fourier tranforms/series
- - uniqueness of positive and negative frequencies for real/hermitian inputs
- - discrete case: resolution in the sampled signal and the frequency spectrum
- sampling as an impulse train
- - convolution theorem
- - corresponding frequency spectrum -- repeated duplicates 
- - changing the sampling rate changes the the location of the duplicates -> nyquist thm
-   