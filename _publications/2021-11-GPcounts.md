---
title: "Non-parametric modelling of temporal and spatial counts data from RNA-seq experiments"
collection: publications
permalink: /publication/2021-11-GPcounts
date: 2021-11-1
venue: 'Bioinformatics, Volume 37, Issue 21, November 2021'
paperurl: 'https://academic.oup.com/bioinformatics/article/37/21/3788/6313161'
citation: 'BinTayyash, Nuha, et al. "Non-parametric modelling of temporal and spatial counts data from RNA-seq experiments." Bioinformatics 37.21 (2021): 3788-3795.'
---

Motivation
The negative binomial distribution has been shown to be a good model for counts data from both bulk and single-cell RNA-sequencing (RNA-seq). Gaussian process (GP) regression provides a useful non-parametric approach for modelling temporal or spatial changes in gene expression. However, currently available GP regression methods that implement negative binomial likelihood models do not scale to the increasingly large datasets being produced by single-cell and spatial transcriptomics.

Results
The GPcounts package implements GP regression methods for modelling counts data using a negative binomial likelihood function. Computational efficiency is achieved through the use of variational Bayesian inference. The GP function models changes in the mean of the negative binomial likelihood through a logarithmic link function and the dispersion parameter is fitted by maximum likelihood. We validate the method on simulated time course data, showing better performance to identify changes in over-dispersed counts data than methods based on Gaussian or Poisson likelihoods. To demonstrate temporal inference, we apply GPcounts to single-cell RNA-seq datasets after pseudotime and branching inference. To demonstrate spatial inference, we apply GPcounts to data from the mouse olfactory bulb to identify spatially variable genes and compare to two published GP methods. We also provide the option of modelling additional dropout using a zero-inflated negative binomial. Our results show that GPcounts can be used to model temporal and spatial counts data in cases where simpler Gaussian and Poisson likelihoods are unrealistic.
