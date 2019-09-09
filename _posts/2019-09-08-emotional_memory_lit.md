---
layout: post
title: ""
author: achennings
date: 2019-08-30
tags: [episodic memory, emotion, RSA]
article_title: ""
article_doi:
---

#### Dunsmoor et al., 2014 _Cerebral Cortex_
[Averisve Learning Modulates Cortical Representations of Object Cortex](https://academic.oup.com/cercor/article/24/11/2859/297931)

__Results__

- Analyses include RSA and PPI following category conditioning.
- Found increased overall neural activity in CS+ related visual cortex
- increased CS+ vs CS- representational dissimilarity in respective category cortices

__Notes__

- Excluded voxels with mean CS+ > CS- activity in RSA to reduce SNR

#### Ritchey et al., 2013 _Cerebral Cortex_
[Neural Similarity Between Encoding and Retrieval is Related to Memory via Hippocampal Interactions](https://academic.oup.com/cercor/article/23/12/2818/464061)

__Methods__


- viewed emotionally negative, positive, or neutral images, 24hr delayed recognition memory test
- computed RSA on item level, or grouped by valence, task (E vs. R), and memory (R vs. F) across items
    + set level groupings _exclude_ item pairs (no diagonal)
- __trial betas were Z-scored according to mean activity within a trial, something that I'm not doing (yet)__
- logistic regression analysis - trial mean ROI activation during either encoding retrieval or with pattern similarity to to predict binary memory outcome
    + significant non-zero coefficient implies mean activation estiamtes and encoding retrieval similarity make sepreateble contributions to memory
    + restricted subsequent memory analyses to regions whihc ER similarity reminaed significant predictor of memory
- also ran a mediation analysis testing if HC activity mediates relationship between ER similarity and 5 choice memory responses

__Results__

- In ROIs with main effect of match level also looked at effect of emotion
    - middle occipital gyrus showed strongest match X emotion interaction
- Found lots of ROIs that vary representations based on _match_ , i.e. (item or set level)
- Also found lots of ROIs that vary representations based on _memory_, regardless of match
- Interaction Match X Memory mostly in MTL and VTC
- Hippocampal mediation analysis found sig. mediation of ER similarity and memory in inferior frontal, inferior parietal, and occipital ROIs
- MOG ER similarity correlated with amygdala activity for negative _remembered_ items more than negaitve _forgotten_ items
- In the end though, HC was more important than Amygdala in predicting memory, suggesting amygdala responses are driven by "recovery and porcessing of item-specific detials"

#### Tambini et al., 2017 _Nature Neuroscience_
[Emotional brain states carry over and enhance future memory formation](https://www.nature.com/articles/nn.4468)

Then relevence here is in the methods, as it might not be fair to compare the emotional --> neutral viewing group the same as our conditioning --> extinction.

__Methods__

- low frequency connectivity of amygdala and anterior hippocampus
    + filter out task frequency to essentially look at "resting state"
- RSA Approach included permutation testing
