---
layout: post
author: macmitch
tags: [medial PFC, lateral PFC, reward, cognitive control, functional loops]
article_doi: https://doi.org/10.1093/cercor/bhx210
---
Duverne, S., & Koechlin, E. (2017). Rewards and cognitive control in the human prefrontal cortex. Cerebral Cortex, 27(10), 5024-5039.

**Goals:** To understand the role of the medial prefrontal cortex (PFC) in driving task-set selection according to reward expectations (as opposed to learned rules)

**Background:** Some studies suggest that the medial PFC facilitates task set selection (switching), but also influences recruitment of lateral PFC regions in relationship to rewards. Additionally, regions in the medial PFC have been conceived to encode reward advantage, choice uncertainty, . 

**Methods:** The task consisted of sequences of colored letters. Participants were asked to discriminate between vowel/consonants and lower/upper case, with one of the tasks providing a greater reward for correct answers on average. No rewards were provided for incorrect responses (also, no losses/punishments). This greater reward advantage pairing to one task set was reversed after a varying number of trials. Green and red letters were paired with specific task sets (rule-based), while other colored letter stimuli were not paired with specific task sets (rule-free).

They applied a reinforcement learning model and a Bayesian model to describe how reward expectations are developed and how they influence task selection on the rule-free trials. The reinforcement learning model assumes that “task values of unchosen tasks are updated in the opposite direction according to reward prediction errors associated with chosen tasks.” The Bayesian model represents the probability that the best rewarded task is one or the other considering all previously chosen tasks and subsequent rewards.

They computed activations maps of regions associated with task selection in the prefrontal cortex (specifically looking for regions with greater activation during rule-free trials). They used these regions to further investigate regions showing activity associated with task value. I am unclear how they specifically set up these task value contrasts.

They conducted a PPI analysis to look at coactivations with the dorsomedial, left and right lateral PFC associated with task value information. 

They conducted an effective connectivity analysis with dynamic causal models (DCMs) to look at interactions between the medial and lateral PFC.

**Results:**
NOTE: rCV (relative chosen task values), rTV (relative values of one task compared to another)

Behavior: task selection favored the more rewarded task set; the more rewarded task set was chosen more often on the rule-free trials; during rule-based trials selection of the less rewarded task set was incongruous with selection biases and thus produced larger RTs

Computational Modeling: both models showed a best fit when task selection choices in rule-free trials were predicted with feedbacks from both rule-based and rule-free trials; the reinforcement learning model fit better than the bayesian model; there is a linear effect of response difficulty in relative chosen task values and an inverted u-shaped function of choice ambiguity in relative chosen task values

Brain activations: bilateral LPC and MPC (pre-SMA and dACC) were engaged in task selection (rather than task execution); activations in this region varied during rule-free (not rule-based) trials in an inverted U function with rTVs (relative values of one task compared to another) supporting the idea that these regions support value-based task selection (maximum values when maximum ambiguity); [I am unclear about some of these results]; BIG IDEAS: MPC and LPC implicated in value-based task selection during rule-free trials and the MPC processes task values in every trial while only guiding task selection in rule-free trials

Functional Connectivity/PPI analyses: activity in bilateral MPC-LPC more correlated with rCVs during rule-free but not rule-based trials; the authors say the functional coupling of MPC-LPC increase with reward magnitude and reward consistency and encode rTV

Effective Connectivity: rCV^2 modulated MPC to LPC connectivity; rCV modulated LPC to MPC connectivity (differentially across trial types); LPC to MPC connectivity increased during task selection (relative to execution) across trial types and reward values

**Discussion:** 
BIG IDEA: Unrelated to task difficulty, the dorsomedial PFC (dmPFC) encodes and conveys reward expectations of the task sets (relative task values; unrelated to actual chosen task sets) to the lateral PFC. Then, the lateral PFC processes task set selection and conveys this information (regardless of chosen task values) back to the dorsomedial PFC.
1. These results support the “distributed view of PFC function” where the dmPFC encodes reward expectations, lateral PFC encodes learned rules of the task sets, and ventromedial PFC encodes reward outcomes associated with task set execution.
2. The dmPFC activations were centered around the anterior pre-SMA and not the dACC, which supports the Kouneiher et al. (2009) findings that pre-SMA is involved in more contextual/immediate processing while the dACC is involved in more episodic/sustained processing.
3. The task sets gained associated reward values in the pre-SMA via model-free reinforcement learning.
4. The lateral PFC subserves the selection of task sets.
5. The lateral PFC integrates reward expectations (from the dmPFC) with learned task set rules. This is consistent with literature findings of bidirectional structural projections between the medial and lateral PFC.
6. Both rule-free and rule-based choice processing are subserved by the same neural architecture. Free choices are processed from the dmPFC to the lateral PFC and back to the dmPFC, while instructed choices are processed from the lateral PFC (regardless of input from the dmPFC). The authors propose a “functional loop” that allows rules to override the reward expectation input on selection processes, perhaps supporting the idea that humans can more flexibly adjust behavior for free choices while learned rules are hard to override afterward.

**Thoughts:**
* This task seems very similar, perhaps the same, as the task used in Kouneiher et al 2009 NatureNeuro. Different in that it specifically targets uncertainty; not episodic/contextual control.
* Look at functional coupling (static FC + dynamic FC) of medial PFC (dACC and pre-SMA) and lateral PFC across rewarded and standard GNG tasks
* Again, this paper focused on the prefrontal cortex. A network approach within an integrated whole-brain systems view would be beneficial for considering relationships with reward processing architecture (subcortical) as well as task execution architecture (motor, cerebellar).
Ask JRC:
1. Selection blocks?
2. Differences between the two models (reinforcement learning and Bayesian) for describing how reward expectations are developed and influence task selection?
3. GLM contrasts used to investigate task values?
4. dynamic causal modeling (compare this method to that used in Kouneiher et al. 2009)
5. rCV v rCV^2 v rTV v rTV^2
