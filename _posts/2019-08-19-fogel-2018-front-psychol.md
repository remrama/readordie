---
layout: post
title: "Fogel et al., 2018, Front Psychol"
author: remrama
date: 2019-08-19 16:04:08 -0500
tags: [dreaming,textanalysis]
article_title: "A Novel Approach to Dream Content Analysis Reveals Links Between Learning-Related Dream Incorporation and Cognitive Abilities"
article_doi: https://doi.org/10.3389/fpsyg.2018.01398
---

I checked this paper out because I stumbled across it as including a "text analytic" approach to measuring dream content. This is something I'm recently (very) interested in, and most of the papers I've found have been solely to focus on that. Here, the analysis is secondary to the testing of hypotheses about dream content, learning, and individual differences. I came for the text analysis, but the experimental design and questions about the memory sources of dream content was really cool. **Also, I found that their intro had some really nice concise reviews and compelling arguments for studying this stuff.**

They asked whether there was a relationship/correlation between amount of task-related dream content _and learning of that task_, and specifically (the novel part) if this relationship was mediated by individual differences, primarily intelligence. This setup seemed largely motivated by David Foulkes [1985](https://doi.org/10.4324/9781315831220), who they cite as proposing a "close link between cognitive capacity and the level of sophistication in dream production." Cool idea that I never really thought about!

They particularly want to avoid focusing on REM dreams. They get _waking_ reports during the afternoon nap after while the participant is lying in bed awake. For sleep reports, they wake people up after the "first signs" of stage 2 sleep! So these are essentially hypnagogic reports, right? Borderline between NREM and hypnagogia I guess (unless those are considered the same?). They split these into early/late dream reports, a bit arbitrarily (I think) by saying the first 4 and last 4 (they collected 8 per subject). All these reports are compared (via semantic similarity) with waking reports of mental content after mentally imaging the task.

| report type      | when |
| :--------------: | :--- |
| mental rehearsal | after mental rehearsal of the task |
| early dreams     | reports 1-4 of waking subj up at first signs of N2 |
| late dreams      | reports 5-8 of waking subj up at first signs of N2 |
| daydreams        | reports of waking subj up after 10 seconds of wake during the nap |


The tasks seemed great, as they were very interactive. The spatial navigation task was a modded version of _Team Fortress_, and the tennis task was a Wii game (each subject did one or the other). I presume these awesome games aided in dream incorporation.

I was particularly interested in their text analysis of dream reports. They use **semantic similarity** implemented via [WordNet](https://wordnet.princeton.edu/) and [NLTK](https://www.nltk.org/) (NLTK provides [direct access](http://www.nltk.org/howto/wordnet.html) to WordNet).

1. Tokenize each dream report
2. Remove punctuation and stop-words
3. Look up the "synsets" for each token/word of each dream report. Synsets are the WordNet synonyms for each word. There are variable numbers within the synset of each word, and different word counts per dream. They include all the words of each synset of each word (so each report ends with a variable number of words).
4. Get Wu-Palmer similarity metric (possible values 0-100) between the mental rehearsal report and each experimental/nap report. Wu-Palmer similarity metric is between two words, so for a single similarity value between waking rehearsal and nap report, they get the similarity between all possible pair-wise combinations of words between the two reports, and then average those together. **This then represents the similarity of experience between waking rehearsal and dream** (sidestepping the waking report condition). This is pretty cool! Of course there is still much to wonder about the distribution of Wu-Palmer scores, although maybe they are so inconsistent that the average is the only useful descriptive anyways??

They found that dream content had more task-incorporation (semantic similarity with mental rehearsal report) than daydreaming.

<p align="center">
    <img src="https://www.frontiersin.org/files/Articles/387144/fpsyg-09-01398-HTML/image_m/fpsyg-09-01398-t001.jpg" width="30%" alt="table 1 from paper" /><br>
    Why not a graph?? :/
</p>

The main mediation analysis to look at a bunch of relationships showed that only early dream report incorporation correlated with task learning. With respect to their main interest in dream incorporation and intelligence, there was a cool finding where cognitive abilities related with amount of dream incorporation -- specifically _dream_ incorporation and not daydreaming.

<p align="center">
    <img src="https://www.frontiersin.org/files/Articles/387144/fpsyg-09-01398-HTML/image_m/fpsyg-09-01398-g005.jpg" width="30%" alt="figure 5 from paper" />
</p>

Unfortunately, it seems they didn't find any effects of cognitive ability and learning, which would have been very cool. But their conclusion that dream incorporation correlates with task performance is cool, and their text analysis (and discussion about it) is very useful to the work I want to pursue.