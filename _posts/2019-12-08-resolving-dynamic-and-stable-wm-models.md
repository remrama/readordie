---
layout: post
author: remrama
tags: [WM, monkey, "neural model"]
title: "Resolving dynamic and stable WM models"
---

Murray et al., 2017, [Stable population coding for working memory coexists with heterogeneous neural dynamics in prefrontal cortex](https://doi.org/10.1073/pnas.1619449114), _PNAS_

One of the recent papers I read had this statement

>Instead, high-resolution pixel-by-pixel representations might be condensed into stable and low dimensional representations in higher cortical regions

and cited this paper I'm writing about. This was a point I wanted to make with our _Cortex_ paper, and so even though there is no distraction involved, I thought this paper was relevant reading.

They ask the main question, how are PFC WM neurons dynamic (ala Stokes) but also working memory representations are stable? Their answer is that despite single-neuron dynamics, population-level representations in PFC are stable.

This article has a really nice intro setting up the "tension" between dynamic and stable coding models.

The analysis in Fig 1 C/D would is a nice simplified way of measuring dynamics of memory representations; Use the end of the memory delay as the "memory representation" and try to decode previously with that.

Fig 1 is about showing how dynamic WM representation are. But after applying PCA to get the "mnemonic subspace," Fig 2 is all about stability.

Notably, they find the mnemonic subspace representation to exist as early as encoding - along with the dynamic representation - suggesting they coexist.

They show that 3 previous models all fail to capture their results, and so build their own "stable subspace" model.