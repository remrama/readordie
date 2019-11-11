---
layout: post
author: macmitch
tags: [resting state functional connectivity, general functional connectivity, heritability]
article_doi: https://doi.org/10.1016/j.neuroimage.2019.01.068
---

Elliott, M. L., Knodt, A. R., Cooke, M., Kim, M. J., Melzer, T. R., Keenan, R., Ireland, D., Ramrakha, S., Poulton, R., Caspi, A., Moffitt, T. E., & Hariri, A. R. (2019). General Functional Connectivity: shared features of resting-state and task fMRI drive reliable and heritable individual differences in functional brain networks. NeuroImage, 189, 516-532.

**Goal:** This paper proposes General Functional Connectivity (GFC) as a more reliable metric of intrinsic functional brain connectivity than the standard usage of Resting State Functional Connectivity (RSFC) in the literature today. GFC results from a combination of resting-state and task-based scans.

**Methods/Results:**
* 1206 participants from the Human Connectome Project and 1037 participants from the Dunedin Study
* In constructing GFC, signal due to task structure was included as a nuisance covariate.
* They utilized the Power 264 atlas with 5-mm spheres in the reliability and prediction analyses and a 44 region parcellation derived from the Yeo 2011 parcellations for the heritability analyses.

* _Test-retest reliability:_ They used intraclass correlation (ICC) to quantify test-retest reliability of intrinsic connectivity at different scan lengths. For RSFC reliability, they found 0.28 (poor) at 5 minutes and 0.54 (moderate) at 40 minutes. For GFC reliability, they found .28 (poor) at 5 minutes and 0.56 (moderate) at 40 minutes.
* _GSR:_ They compared the ICCs when the analyses were run with and without global signal regression. They found that ICCs were significantly greater without global signal regression. However, they state that this could perhaps be due to stable propensities for movement and thus correlated motion artifacts. Thus, they conducted the rest of the analyses conservatively and included global signal regression.
* _Network specificity in reliability:_ They found differences in network reliability, with the limbic system showing the least reliability across all scan lengths. They found that the DMN and FPN showed the greatest reliability with moderate reliability at just 10 minutes of scan time increasing to almost excellent reliability at 40 minutes of scan time for both RSFC and GFC. Network specific increases in reliability were largely equivalent for both RSFC and GFC.
* _Heritability:_ They used the ACE modeling of twin data from the HCP dataset. They found that with increasing scan time the additive genetics component (A) increased significantly, with GFC consistently showing greater contributions than RSFC. Additionally, they found that the non-shared environment and error component (E) decreased significantly with increasing scan time, while the shared environment component (C) stayed about the same across all scan lengths.
* _Intrinsic connectivity and cognitive ability:_ They used connectome-base predictive modeling (CPM) to predict cognitive ability. Leave-one-out cross validation was used to make within-sample predictions. While 40 minutes of both RSFC and GFC could predict cognitive ability, no statistical significance was found between RSFC and GFC. So, they trained models on the Dunedin Study to predict cognitive ability in the HCP sample and found that the GFC model had greater predictive validity than the RSFC model. Additionally, the GFC model performed at least as well if more better than all other single-task predictive models (emotional processing, reward processing, executive control).

**Discussion:**
* The authors suggest GFC as a more useful measure of intrinsic functional connectivity since combinations of task-based and resting state data create longer scan lengths and perform at least as well or better than RSFC in predicting cognitive ability.
* The authors emphasize the necessity for improved reliability estimates in individual differences research and suggest the use of GFC instead of short scan length RSFC as is commonly used currently.
* They also emphasize that, considering their results showing that additive genetics component increases significantly with increased scan length, scan length should be considered when conducting genetics research.
* They defend GFC against the proposed critique of introducing heterogeneity into intrinsic connectivity with the following three points. (1) RSFC is already heterogenous in and of itself considering differences in acquisition and the influence of thought content, caffeine, recent tasks, and sleep. (2) The results of GFC largely agreed between the two studies (HCP and Dunedin) despite differences in population, scanners, and tasks. (3) The fundamental nature of reliability limits the utility of associations drawn from unreliable methodologies, so the gains in reliability achieved with GFC outweigh the potential heterogeneity introduced.

**Thoughts:**
* I am pretty unclear on the functionality of some of these methods (i.e., ICC, leave-one-out-cross validation, and CPM). I will look into these further.
* What, if any, implications does this have for specific task-based functional connectivity? The tasks included in GFC controlled for task-based signal changes, but this indicates that the underlying neural architecture is largely similar across tasks. This isn’t necessarily surprising, but it is interesting to keep in mind moving forward. This would make it complicated to compare between task-based FC and resting-state FC if we were to move toward using GFC instead.
* This study compares RSFC and GFC network reliability, but does not compare network membership between the methods. I would be interested in looking at differences in network clustering between these approaches.
