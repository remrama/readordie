---
layout: post
author: tnugiel1
tags: [ADHD, ASD, functional connectivity, EF, FPN, DMN, GIMME, ABBA]
article_doi: http://dx.doi.org/10.1101/490672. 
---

Overview: This paper takes a look at the idea that neural profiles of co morbid disorders are trans-diagnostic and exist on a continuum as opposed to categorical in the way they are diagnosed. The paper tests for different functional connectivity profiles of systems recruited for executive functions in a group with an ASD, ADHD, as well as TD individuals. To delineate EF networks a cognitive flexibility task was used to choose ROIs from established resting state networks. The authors predicted that across the three groups there would be three subtypes of neural profiles. A group of mostly TD individuals with typical or above average EFs and mature looking connectivity profiles ie strong within network coherence and negative relations between FPN and DMN. They expected a second subtype with more immature neural profiles such as stronger between network connectivity and either younger TD individuals with weaker EF or older ADHD individuals with stronger EF or individuals with ASD and moderately elevated ADHD. Lastly they predicted a third subtype with ADHD or ASD and EF impairments and aberrant network structures as opposed to just immature ones. 

Methods: Participants - 132 8-13 year old TD N = 53, ADHD N = 43, AD N = 36 
Behavioral measures - CBCL, RBSR, Conners, BRIEF
fMRI data  - resting state scans were collected, varying length protocols were used (especially for those with ASD) so a minimum of 156 volumes or 6.5 minutes were kept. Individuals were asked to refrain from taking any stimulant medication the day of the scan.
Preprocessing - >3 mm in any direction cutoff for motion plus ICA artifact removal. WM and CSF were regressed out. Linear trend and RS bandpass filtering were done with normalization into standard space. 
ROI selection: ROIs were taken from an adult study of a cognitive flexibility task and matched up with ROI labels from 4 power network, DMN, FPN, Salience, and sub-cortical regions. They specifically did not want many ROIs since the GIMMME method they used works better with fewer.
GIMME - Essentially uSEM using both contemporaneous and time lagged effects in an autoregressive manner to estimate directionality of FC relationships. GIMME starts with a null model and iteratively estimates paths to see if they improve model fit. It does this at the individual level and then subgroups are identified using a walktrap method and repeating the same iterative process at the subgroup level. A hierarchical clustering validation metric was used to evaluate the walktraps solution.

Results - while there was good model fit for all the data individually walktrap came up with a three subgroup solution that was not supported by either clustering metric. Modularity was also not different between the three groups. The authors take this to suggest there is no valid subtyping of these networks within this heterogeneous sample. 


Thoughts: GIMME GIMME GIMME a model after midnight, okay need to definitely tear into this method more. Interesting why the authors specifically focused on cogflex ROIs from that task though they did seem to hit key nodes in the four network. I wonder though if pick fewer ROIs is limiting variability and minimizing patterns of connectivity that might be distinct in these groups. 
