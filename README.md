# On-nonparametric-density-estimation-on-linear-and-nonlinear-manifolds
Matlab codes (written in version 2016b) to implement density estimation by inverse Radon transform on linear and nonlinear manifolds, as described in https://arxiv.org/pdf/1901.03780.pdf. You will need the IRtools codes in your directory before using this code. They can be found here https://github.com/jnagy1/IRtools,
Further descriptions of the codes are given in the code files in the main zip.
example 1 (in the main zip) runs algorithm 1 of https://arxiv.org/pdf/1901.03780.pdf with densities 1-4 as described in the same paper.
example 1 script can be used to reproduce figures 6-9 (and all figures in the supplementary material), and the results of tables 1 and 2, by varying the input density and sample size m.
example 2 reproduces figure 11 and can be tweaked to do density estimation on 2-D patches of any manifold using PCA.
varying kappa and r in example 2 can be used to reproduce the errors in table 3.
