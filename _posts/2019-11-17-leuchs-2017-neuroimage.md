---
layout: post
author: achennings
tags: [pupillometry, fear conditioning, dACC]
---

[Leuchs et al., 2017. Neural correlates of pupil dilation during human fear conditioning. _NeuroImage_.](https://doi.org/10.1016/j.neuroimage.2016.11.072)

## Motivation
SCR sucks, like big time. Pupil diameter might be a better physiological marker than SCR. Let's find out together.

## Introduction

### Background
- Pavlovian fear conditioning and extinction are useful tools for studying emotional learning & PTSD
- SCR is usually the main index of sympathetic arousal, and is usually measured as CS+ vs. CS-
- Can also use startle, but this changes the structure of the task slightly
- Disadvantages of SCR
    + don't have to convince me, I know first hand how noisy and unreliable it can be
- Pros of pupillometry
    + neutral measuer (compared to EMG startle)
    + easily implemented in fMRI (we'll see)
- tonic changes linked to general alertness and wakefulness
- Most importantly, the pupil dilates in response to aversive and emotionally arousing stimuli
    + so we can use it as a read out of fear/threat related processing
- Not only increases to CS+, hints of contraction to CS-, so could act as readout of fear inhibition
- Since there are no direct cortical inputs to muscles controlling pupil response, probably mediated by the Locus coeruleus (LC)

### Quantifying responses
- usually baselined to pre-trial responses
- either take mean during CS presentation, 
- or take peak change from baseline
    + in this method, people have shown that peak is usually right before US presentation

## Goal
Describe the neural correlates of pupil dynamics during conditioning and extinction, with the hypothesis that these regions will overlap with normal fear/extinction network. If true, then pupillometry is indeed a good measuer of physiological reactivity during conditioning experiments.

## Methods

- N=34
- simple task, CS were colored squares, and were either CS100+, CS60+, or 0% (CS-) reinforced
- Extinction was between groups for different CS+
- Some details about excluding certain trials for analysis based on some pupil data, not worth copying here but refer back to article for details. In sum no more than 5 trials removed per subeject
- GLM relating pupillometry to neural activity modeled both as single PM regressor and as seperate modulators

## Results

- neural correlates of pupil diameter match eactly the fear map. QED son.
- really not much else to say - it was a simple paper with a good point. will be incorporating this into my analyses whenever possible.
- No PREE effect, kinda interesting, but we would never use a CS100+
