---
title: "Adaptive Gaussian nested filter for parameter estimation and state tracking in dynamical systems"
collection: publications
category: conferences
date: 2023-06-04
citation_with_links: '<strong>Pérez-Vieites, S.</strong>, & <a href="https://victorelvira.github.io/">Elvira, V.</a> (2023). Adaptive Gaussian nested filter for parameter estimation and state tracking in dynamical systems. In <i>ICASSP 2023-2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)</i> (pp.1-5). IEEE.'
# permalink: /publication/2024-02-17-paper-title-number-4  # Commented out - no individual page
abstract: 'We introduce the adaptive Gaussian nested filter (AGNesF), the first nested method that adapts the number of samples to estimate both the static parameters and the dynamical variables of a state-space model. The proposed method is based on the nested Gaussian filter (NGF), that combines two layers of inference, one inside the other, to compute the joint posterior probability distribution of the static parameters and the state variables. We propose two novel rules to reduce computational complexity without compromising the performance. One enables the bottom layer techniques to run recursively, while the other reduces automatically the number of samples in the parameter space when they are redundant. We describe a specific implementation of the new scheme that uses a quadrature Kalman filter (QKF) in the parameter layer, and we study its performance in a stochastic Lorenz 63 model.'
paperurl: 'http://sarapv.github.io/files/paper/perez2023adaptive.pdf'
doiurl: 'https://doi.org/ 10.1109/ICASSP49357.2023.10094865'
bibtexurl: 'http://sarapv.github.io/files/bibtex/perez2023adaptive.txt'
#arxivurl: 'https://arxiv.org/abs/1234.5678'
---