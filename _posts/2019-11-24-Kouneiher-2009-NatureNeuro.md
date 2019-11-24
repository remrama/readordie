---
layout: post
author: macmitch
tags: [motivation, cognitive control, hierarchy, episodic, contextual]
article_doi: https://doi.org/10.1038/nn.2321
---

Kouneiher, F., Charron, S., & Koechlin, E. (2009). Motivation and cognitive control in the human prefrontal cortex. Nature neuroscience, 12(7), 939.


**Goal:** Investigate the hierarchy of motivation processing in the medial frontal cortex. 

**Background:** Posterior lateral PFC (lPFC) supports transient control (contextual control), while the middle lPFC supports sustained control (episodic control). Medial frontal cortex supports processing of motivation in behaviors (e.g., error monitoring). Hypothesized a posterior-anterior organization of the medial frontal cortex aligning with organization of the lPFC involved in executing contextual (posterior) and episodic (middle) control.

**Methods:** The task consisted of sequences of colored letters in a 2x3 design with both low and high incentive blocks across baseline, contextual, and episodic control conditions. Participants were asked to discriminate between vowel/consonants and lower/upper case depending on the color of the stimuli. In the contextual control condition, red and green letter stimuli were consistently each paired with a task set (vowel/consonant and lower/upper case, respectively). In the episodic control condition, blue and yellow letter stimuli task associations switched partway through the block. Participants were asked to ignore black distractor letters. Half of the trials contained boxes around the letter stimuli, indicating extra high incentives for correct performance (and extra high losses for errors; solid boxes) as well as marginal increased incentives for correct performance (and marginally higher losses for errors; dashed boxes).

Activation map contrasts were computed for contextual control (interaction between trial type and block type: contextual > baseline compared to default trials), episodic control (main effects for block type: episodic > contextual), contextual motivation (bonus trials high incentive > bonus trials low incentive compared with standard trials), and episodic motivation (all trials high incentive blocks > all trials low incentive blocks).

Effective connectivity analyses were conducted using SEM on these activation maps. BOLD signal timeseries were collected for each subject at the activation peaks from these previously constructed activation maps and then fed into the SEM.

**Results:**
Cognitive control
* Contextual control activations: left posterior PFC (i.e., IFG)
* Episodic control activations: left middle lateral PFC (i.e., MFG)
* Effective connectivity of control: confirmed directionality of connections from middle to posterior lPFC
* Behaviorally, rt and error rates increased from baseline to contextual to episodic blocks (task trials, not default trials).
Motivation
* Behaviorally, rt increased in the bonus incentive blocks (across episodic, contextual, and baseline control conditions), while accuracy was not affected
* Contextual motivation activations: pre-SMA (post-MFC), IFG, left post-LPC
* Episodic motivation activations: dACC, left and right (MFG) mid-LPC
Integration of motivation and cognitive control
* contextual motivation activations and behavioral effects were independent of cognitive control demands
* effective connectivity from left middle to posterior lPFC increased with episodic control demands, as predicted
* effective connectivity from MFC to lPFC was related to motivation (but not control demands) such that contextual motivation increased effective connectivity between pre-SMA and right post-lPFC and episodic motivation increased effective connectivity between dACC and bilateral mid-LPC (MEM: this sounds like the big idea of this paper - it validates the posterior-anterior contextual-episodic organization of motivation and control interactions)

**Discussion:** These findings support the proposed lPFC organization as posterior-anterior contextual-episodic, respectively. These findings also support the idea that cognitive control processing proceeds according to temporal structure instead of event complexity (what does this mean??). Behavioral performance was related to posterior lPFC activity rather than middle lPFC and MFC activity. The left hemispheric dominance in this paper could be due to language processing due to the use of orthographic stimuli. The authors summarize that the pre-SMA registers response-conflict as the cost of immediate performance (contextual), while the dACC processes performance difficulty and cost across time (episodic). The authors attribute the MFC with the role of conducting cost-benefit analyses for the allocation of cognitive resources. 

BIG IDEAS: Motivational incentives register in the MFC, motivational incentives modulate lPFC activity and effective connectivity between MFC and lPFC, these motivational effects are associated with slower rt, motivational processing in MFC is organized parallel to the control processing in the lPFC (middle = episodic, posterior = contextual)

In the information theory framework, the activity in the lPFC can be conceptualized as the “sum of two energetic forces” stemming from (a) control processing endogenous to the lPFC that facilitates decision making and (b) amplification of this activity from the motivation processing.

**Thoughts:**
In episodic blocks, stimuli color and associated task set was variable (dependent on instruction cues), this added complexity seems to require more flexibility. Why would this be episodic rather than contextual control?

Questions to walk through with Jess:
1. episodic v contextual control in this task paradigm
2. the ANOVA contrasts for isolating activation for each type of control
3. Effective connectivity v dynamic causal modeling (Doesn’t SEM require assumptions of directionality? This doesn’t seem data-driven like they describe.)
4. why are they using dummy regions in the SEM?
5. what is the purpose of the PPI analysis here?
6. statistical mechanics of neural network theory (information theory)

It seems like the posterior-anterior organization of contextual-episodic control described here disagrees with the rostrocaudal hierarchical gradient described in Bahlmann et al., 2015. 

Why would the extra incentives increase rt (poorer performance)? Could this relate to the idea postulated in adolescents in Teslovich et al., 2014 of accumulating evidence when greater rewards/losses were at stake?

This paper is careful to restrict their findings to the frontal cortex. This makes me wonder if they found other results of motivation or cognitive control or the interaction between the two but did not report them here. Using a whole brain approach would be helpful as the frontal cortex does not act in isolation.

The authors state that MFC activations were unrelated to control demands (baseline, contextual, episodic). However, they also note that the dACC activity varies with performance difficulty. So, while BOLD signal did not vary significantly between default and task trials, it did vary between control block task types.
