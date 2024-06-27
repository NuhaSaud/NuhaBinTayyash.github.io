---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap"><a href="{https://academic.oup.com/bioinformatics/article/37/21/3788/6313161}">Non-parametric modelling of temporal and spatial counts data from RNA-seq experiments</a> 

Abstract
Motivation
The negative binomial distribution has been shown to be a good model for counts data from both bulk and single-cell RNA-sequencing (RNA-seq). Gaussian process (GP) regression provides a useful non-parametric approach for modelling temporal or spatial changes in gene expression. However, currently available GP regression methods that implement negative binomial likelihood models do not scale to the increasingly large datasets being produced by single-cell and spatial transcriptomics.
Results
The GPcounts package implements GP regression methods for modelling counts data using a negative binomial likelihood function. Computational efficiency is achieved through the use of variational Bayesian inference. The GP function models changes in the mean of the negative binomial likelihood through a logarithmic link function and the dispersion parameter is fitted by maximum likelihood. We validate the method on simulated time course data, showing better performance to identify changes in over-dispersed counts data than methods based on Gaussian or Poisson likelihoods. To demonstrate temporal inference, we apply GPcounts to single-cell RNA-seq datasets after pseudotime and branching inference. To demonstrate spatial inference, we apply GPcounts to data from the mouse olfactory bulb to identify spatially variable genes and compare to two published GP methods. We also provide the option of modelling additional dropout using a zero-inflated negative binomial. Our results show that GPcounts can be used to model temporal and spatial counts data in cases where simpler Gaussian and Poisson likelihoods are unrealistic.</div>

  <div class="wordwrap"><a href="{https://link.springer.com/chapter/10.1007/978-3-319-07467-2_39}">Differential Diagnosis of Erythemato-Squamous Diseases Using Ensemble of Decision Trees</a> 

Abstract
The differential diagnosis of erythemato-squamous diseases (ESD) in dermatology is a difficult task because of the overlapping of their signs and symptoms. Automatic detection of ESD can be useful to support physicians in making decisions if the model gives comprehensible explanations and conclusions. Several approaches have been proposed to automatically diagnosis ESD, including artificial neural networks (ANN) and support vector machines (SVM). Although, these methods achieve high performance accuracy, they are not attractive for dermatologists because their models are not directly usable. Decision trees can be converted into a set of if-then rules, which makes them particularly suitable for rule-based systems. They have been already used for the diagnosis of ESD. In this paper, we investigate the performance of boosting decision trees as an ensemble strategy for the diagnosis of ESD. We consider two decision tree models, namely unpruned decision tree and pruned decision tree. The experimental results obtained on UCI dermatology data set show that boosting decision trees leads to a relative increase in accuracy that attains 5.35%. Comparison results with other related methods demonstrate the competitiveness of the ensemble of unpruned decision trees. It performs 96.72% accuracy, which is better than those of some methods, such as genetic algorithms and K-means clustering.
    
    
<div class="wordwrap"><a href="{https://dl.acm.org/doi/abs/10.1145/2908961.2931632}"> BeamGA Median: A Hybrid Heuristic Search Framework </a>
    
Abstract 
BeamGA is a general hybrid heuristic framework that can be used to solve the median problem in comparative genomics, where any distance function can be used. It starts with a heuristic search approach (local beam search) in order to generate a number of solutions. Then a Genetic Algorithm (GA) is applied to refine the solutions. It considers true biological evolution scenarios by applying the concept of common intervals during the GA optimization process.
    
    
    
<div class="wordwrap"><a href="{https://publications.waset.org/10007366/beamga-median-a-hybrid-heuristic-search-approach}"> BeamGA Median: A Hybrid Heuristic Search Approach </a>
    
Abstract 
The median problem is significantly applied to derive the most reasonable rearrangement phylogenetic tree for many species. More specifically, the problem is concerned with finding a permutation that minimizes the sum of distances between itself and a set of three signed permutations. Genomes with equal number of genes but different order can be represented as permutations. In this paper, an algorithm, namely BeamGA median, is proposed that combines a heuristic search approach (local beam) as an initialization step to generate a number of solutions, and then a Genetic Algorithm (GA) is applied in order to refine the solutions, aiming to achieve a better median with the smallest possible reversal distance from the three original permutations. In this approach, any genome rearrangement distance can be applied. In this paper, we use the reversal distance. To the best of our knowledge, the proposed approach was not applied before for solving the median problem. Our approach considers true biological evolution scenario by applying the concept of common intervals during the GA optimization process. This allows us to imitate a true biological behavior and enhance genetic approach time convergence. We were able to handle permutations with a large number of genes, within an acceptable time performance and with same or better accuracy as compared to existing algorithms.
    
 