---
layout: post
author: macmitch
tags: [reward, inhibition, adolescence]
article_doi: https://doi.org/10.1093/cercor/bhp225
---

Geier, C. F., Terwilliger, R., Teslovich, T., Velanova, K., & Luna, B. (2009). Immaturities in reward processing and its influence on inhibitory control in adolescence. Cerebral cortex, 20(7), 1613-1629.

**Background:** The authors suppose that two primary systems largely contribute to risk-taking during adolescence: reward processing and inhibitory control. Past work has demonstrated that reward processing is dynamic with at least two stages: anticipatory processing (initial detection and evaluation) and consummatory processing (post reward processing relative to prediction). Additionally, development of dopamine systems across adolescence (increased DA inputs to PFC, shift from mesolimbic to mesocortical DA systems, density of DA transporters peaks) likely contributes to the interactions between these systems. 

**Methods:** The authors used an antisaccade task with monetary incentives and two partial “catch” trial variants to separably look at brain activity during three phases: cue identification, response anticipation, and response feedback. Eyetracking was used to measure performance on the antisaccade task; variables of interest are (1) correct AS latencies, (2) incorrect AS latencies, (3) correct AS response rate ((1 – [inhibitory failures])/[total scorable trials]). 

fMRI data was deconvolved with 6 orthogonal regressors of interest (reward cue, neutral cue, reward prep, neutral prep, reward saccade response, neutral saccade response, correct AS trials only) and an impulse response function was estimated (IRF) for each regressor of interest to reflect the estimated BOLD response to each type of stimulus after controlling for the others. ROIs were determined a priori for reward (vStr, OFC, vmPFC) and oculomotor control (sPCS, iPCS, paraCS, dACC, cACC, IPS, putamen, dlPFC). Ran an ANOVA on the IRF timecourses with time, incentive, and age as factors.

**Behavioral Results:**
* Adolescents showed significantly more correct ASs on rewarded as compared to neutral trials. Adults did not show significantly more correct ASs on rewarded compared to neutral trials (but it was trending).
* Both adults and adolescents showed shorter correct AS rts on rewarded compared to neutral trials.

**fMRI Results:**
* During the monetary incentive cue period, adults showed more positive activity in right vStr during rewards while adolescents showed a negative response to both reward and neutral cues in the right vStr. Also during the monetary incentive cue period, adolescents showed similar activity in oculomotor and inhibitory control regions during the reward trials but not during the neutral trials.
* During the response preparation period, adolescents showed greater right vStr activity during reward compared to neutral trials. Adults showed no significant activity in the right vStr during the response preparation period. Also during the response preparation period, adolescents showed greater activity in control regions (left sPCS, right MFG/SFG, left iPCS, posterior parietal) than adults during rewarded compared to neutral trials.
* During the saccade response period (AKA response feedback), adolescents showed greater activity in the left OFC during neutral trials. Adolescents also showed greater activity in the right ACC during neutral trials. In the left ACC, adults showed greater initial positive activity during reward, while adolescents showed greater negative activity during reward and greater positive activity during neutral trials.

**Discussion:** Most notably, adolescents (compared to adults) showed attenuated activity in VS during the cue, and greater activity in the VS and sPCS during response preparation on reward trials. Accompanied with the result that adolescents (compared to adults) improved correct response rate during the reward trials, the authors take this to mean that adolescents may be particularly sensitive to reward modulation on inhibitory control (compared to adults). 

While adults and adolescents recruited a largely similar network of brain regions during the task, adolescents showed differential recruitment of reward and control regions suggesting immaturities in both reward and inhibitory control. 
* During the cue period, adolescents had initial negative response which was very similar for reward and negative trials. The authors concluded that the valence of the cues were not being processed separately. During the cue period, adults showed activity in right vStr during reward but not neutral trials indicating some differentiation between reward and neutral cues. The authors suggest that differences in dopamine signaling between age groups could underlie this difference in processing the cue. Adolescents engaged control regions more and adult engagement was temporally extended during rewarded trials; this indicates the increased salience of these trials compared to neutral trials. Reflecting an immaturity in control recruitment, adolescents may rely on frontal exec systems in a similar way to adults during tasks with more cognitive load (greater difficulty).
* Adolescents showed both an initial decrease in activity in response to initial cues (underactivity) followed by an increase in activity in response to reward preparation (hyperactivity). This could explain a disagreement in the literature on whether adolescents underactivate or hyperactivate the vStr in response to rewards. 
* The authors suggest that mature reward-motivated control behavior may rely on the consistent integration of multiple brain regions, specifically including the PFC. And, immaturities in this system may bias toward risk-taking behaviors during adolescence.


**Thoughts:**
* The temporal differences in reward processing shown here in response occur on the order of 3 seconds. The dynamic functional connectivity approach I am proposing will not get at this fine grained of a level. Additionally, our go/no-go task does not have separable periods for cue – preparation – execution. Perhaps all we can capture is differences (on the order of ~40 seconds) in consistency of functional connectivity across the task. However, does knowing that reward circuitry does show fine grained temporal differences in activation impact the results I could draw from my dfc analysis. Not in the way I have asked the question now, but I do wish there was a way to look at dfc on the order of ~3 seconds.
* I need to look deeper into the mechanism supporting the utility of the catch trials.
