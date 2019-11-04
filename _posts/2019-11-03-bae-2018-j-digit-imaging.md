---
layout: post
title: "Bae et al., J Digit Imaging"
author: achennings
date: 2019-11-03
tags: [functional connectivity, schizophrenia, fcma]
article_doi: https://doi.org/10.1007/s10278-017-0020-4
---
#Differences between Schizophrenic and normal subjects using network properties from fMRI

## Overview
My rational for picking this paper is that it uses a full correlation matrix analysis (fcma) to compare whole brain functional connectivity between a control group and a patient group, which is something I am interested in doing.

The goal of this paper is to use machine learning and graph theory to try and predict a diagnosis of scz.

## Image Acquisition
- used previously available dataset of scz patients and matched controls
- 54 controls, 21 scz
- all performed a n-back task
- 4mm isotropic voxel size, 2.5s TR

## Analysis
- Feature selection
    + motion correct & register time series data
    + compute fcma
        * BASCO auto selection of 90 ROIs
        * I think they reduced activity down to an ROI timecourse
        * 90x90 spearmans correlation matrix
        * critical threshold of top 5% of correlations
        * absolute of any element that had a value greater than .5 was set to 0 to reduce noise and to reuce redundancy while transforming data
    + extract network properties using correlation matrix
        * average neighborhood connectivity, clustering assortativity, etc.
    + feature reduction
        * relief algorithm selected top 9 features
- Classifier
    + K-nearest neighbor, SVM, decision tree, naive bayes, and discriminant analysis (DA) classifiers
    + for all algorithms, used 10-fold xval procedure
- there were some feature differences between groups
- pretty good classification overall - it works

## Discussion
- 9 features from a single scan is sufficient to differentiate between scz and controls
- there were some interesting graph theory findings when comparing across group
- SVM had highest accuracy

I was a little underwhelmed by this paper, especially because I don't use graph theory or study scz but o well.