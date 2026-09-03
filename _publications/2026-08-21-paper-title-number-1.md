---
title: "When Less is More: Understanding When Token Filtering Helps and Fails in AI-generated Text Detection"
collection: publications
category: conferences
permalink: /publication/2026-08-21-paper-title-number-1
excerpt: 'The rapid advancement of large language models (LLMs) has made AI-generated text detection increasingly critical. Existing zero-shot detectors assume that more token-level evidence leads to more reliable detection. However, our empirical study challenges this consensus: fewer tokens sometimes work better, retaining only 40% can yield optimal performance, yet this benefit is not universal. Using the Entropy Gap Score (EGS), we introduce top-$k$ cumulative probability filtering as a diagnostic probe. Across three representative settings, filtering exhibits strikingly different behaviors. We analyze EGS via typical set theory and quantify its dynamics through entropy calibration and distribution analysis. We find that filtering helps for weak source LMs, where low-entropy tokens are harmful, but fails for strong source LMs, where they are not notably harmful. Our work provides the first systematic analysis showing that some tokens are not merely uninformative but systematically harmful due to entropy miscalibration, revealing a two-sided trade-off in token-level detection.'
date: 2026-08-21
venue: 'EMNLP 2026 (Main Conference)'
slidesurl: ''
paperurl: 'https://arxiv.org/abs/2608.29903v1'
bibtexurl: ''
citation: ''
---
The rapid advancement of large language models (LLMs) has made AI-generated text detection increasingly critical. Existing zero-shot detectors assume that more token-level evidence leads to more reliable detection. However, our empirical study challenges this consensus: fewer tokens sometimes work better, retaining only 40% can yield optimal performance, yet this benefit is not universal. Using the Entropy Gap Score (EGS), we introduce top-$k$ cumulative probability filtering as a diagnostic probe. Across three representative settings, filtering exhibits strikingly different behaviors. We analyze EGS via typical set theory and quantify its dynamics through entropy calibration and distribution analysis. We find that filtering helps for weak source LMs, where low-entropy tokens are harmful, but fails for strong source LMs, where they are not notably harmful. Our work provides the first systematic analysis showing that some tokens are not merely uninformative but systematically harmful due to entropy miscalibration, revealing a two-sided trade-off in token-level detection.