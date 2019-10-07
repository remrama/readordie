---
layout: post
author: tnug
tags: [global signal, resting state, functional connectivity]
article_doi:   https://doi.org/10.1038/s41598-019-50750-8
---

Overview: We are going from a tale as old as time to a hot topic debate. Global signal (GS) defined as the average signal from every grey matter voxel in the brain is typically regressed out, thought to be all noise and no signal. This is not uncommon practice but certainly not universally accepted. Issues such as creating spurious negative correlations and potentially artificially introduce correlations, or mess with the direction of existing correlations before regressing it out. One major plus of regressing out GS is improving (as in decreasing) the relationship between head motion and functional connectivity known to rife with artifact. However correlations between GS and each voxel in the brain reveal different weighted correlations with different functional networks and  and these correlations differ in a seemingly meaningful way across groups. All this suggesting that GS is more than just noise. The spatial structure of variability in GS however has not been established and that is what this paper is setting out to do. 

Methods: data - HCP data from 1094 participants adults 22-37. .7 s TR ~14 minutes of rest per scan.

Data processing - Data was brought into surface space and motion corrected dropping frames with fd > .2 or DVARS > 75 with five contagious frames necessary to keep. 1028 subjects in the final group. 

Analysis - GS was averaged across every vertex then GS and a vector of 1s (ie GLM) were regressed on the signal for every vertex. This created a beta weighted map of GS across the vertices. These were computed separately for each run and then averaged across runs. CCA was run for correlations between GS and behavior in their words 'CCA is a natural choice of method because this machine-learning algorithm computes linear combinations of the original variables for each of two multivariate datasets that, together, maximize the linear correspondence between both variable sets'. Data was reduced with PCA before CCA to 100 behavioral and 100 global signal components. CCA outputs were the overall strength of the correlation between each pair. Permutation tests were used to test the CCA significance.  



Results: GS - Mean global signal map across individuals revealed strongest global signal relation in visual cortex, posterior insult, central sulcus and cingulate sulcus. Standard deviation of GS beta maps revealed highest variation in retrosplenial and visual cortex. A PCA was also done on all subjects maps reveal patterns of weights that looks like FP, DMN, dorsal attention and sensorimotor and visual networks. 
CCN results - there was a relationship between the components derives from the PCA on the GS maps and the PCA on the behavioral maps. The positive weights were in the FP networks with negative weights in visual and motor networks. Behavioral weights seemed to line up with positive (education, vocal, K discounting, spatial reasoning) and negative traits (aggressive behavior, anisocial personality, drug use). Supplementary analyses revealed these relationships were not motion driven. 

Thoughts: So GS carries some signal in it, (not just in the name) but it carries some information that seems to be related to behavior. The question though - is it uniquely related to behavior - like does it carry MORE signal than the danger of keeping in a lot of motion and artifact noise? This is where I think the question still lies and there isn't a specific recommendation offered by the paper. I'm a little lost on the weights aspect of the CCN, need to dig more into that. 
