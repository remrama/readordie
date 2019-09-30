---
layout: post
author: tnugiel
tags: [dyslexia, deficit, visual, learning, reading, phonological]
article_doi:  http://dx.doi.org/10.1101/773853
---

Overview: This paper addresses a tale as old as time question in the LD and dyslexia literature. It posits two really prominent but kind of impossible to be parallel ideas about dyslexia. One is that dyslexia is a heterogeneous disorder with difficulties with a myriad of cognitive processes giving rise to th disorder. Phonological processing and rapid naming seem to be the best predictors or account for a lot of variance in reading skill (decoding primarily which is the deficit characterizing dyslexia). And in the other corner the opposing theory is a single 'core' deficit in sensory processing that has a cascading effect. While there is some support for a core deficit presented by evidence that visual processing accounts for variance above and beyond phonological processing in reading skill. One of the issues with the core deficit is that there is no consensuses about what that deficit is, some candidates are the magnocellular pathway deficit, a statistical learning deficit, etc. The current study addresses this issue by using computational modeling of a visual motion detection task which separates the 'pure' sensory components of the task. They test models predicting reading skill  from these components and other correlates of dyslexia to test the idea of this core deficit.  

Methods: Participants - 119 Native English 8-12 varied reading ability impaired and non-impaired. From the Healthy Brain Networks 124 children with specific learning disorder with impairment in reading with with the ctopp and a control group of 119 matched on non-verbal IQ.
Measures - battery of reading and cognitive tests including LWID, Word attack, TOWRE, CTOPP, WASI. 
Psychophysics task- a random array of dots were displayed and participants had to indicate if they were moving to the left or to the right. Motion coherence (how many dots were moving in the same direction) was manipulated to push around motion detection. 
Analyses - Full DDM was fit including, starting point, trial to trial variability in drift rate and and variability of residual time. 
Stepwise regression was used to test for parameters predicting reading skill, age, nonverbal IQ and ADHD dx were included in all models. Mediation was tested as well.


Results: From the healthy brain network sample both a QDA classifier and a SVM using ctopp and RAN were able identify ~ 66 % of individuals with dyslexia from control supporting the multifactorial view of dyslexia but still failed to identify many cases of dyslexia. Age was tested as an interaction and was not significant. Visual processing from the motion detection task was used. Task RT but not task accuracy was related to reading skill. Poor readers made more 'fast errors'. At all levels of stimuli coherence sensory parameter drift rate predicted reading skill with model fit increasing with coherence. In individuals with dyslexia with unimpaired phonological awareness drift predicted reading skill. Decision making DDM parameters (as opposed to purely sensory) were also related to reading skill. So sensory and non-sensory task parameters predicted reading outcomes. Psychophysical measures were tested as simply proxies for phonological awareness but they were not, lastly mediation was tested as the 'cascading effect' however there was only partial mediation of sensory components on PA so nah. 

Thoughts: This is a lot of methods to reach a pretty parsimonious conclusion that the cascading core deficit model isn't supported by this data but it is more than phonological awareness. All in all this paper uses a lot to kind of say a little. Maybe I miss brains. 
