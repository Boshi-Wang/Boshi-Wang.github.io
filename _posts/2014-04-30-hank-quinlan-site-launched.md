---
layout: post
title: "Compression and Kolmogorov Complexity"
date: 2021-10-01
---

Taking a high viewpoint, the modern (neural) AI systems we have today could be seen as a big collection of architectural 
heuristics which people find useful empirically. Take the example of natural language processing (NLP) systems. 
Neural NLP models began popular when attention mechanism was introduced in machine translation, which was a 
landmark where for the first time, neural models outperform traditional methods based on feature engineering with domain knowledge. 
The idea of attention is very simple: when we translate a piece of text, we tend to focus on different parts of the input at different stages.
This leads to its formal implementation, which uses similarities to aggregate hidden representations of each input unit, and pass that aggregated
message as additional information for predicting the current step output. From then on, better heuristics are found, including
Transformer - perhaps the most significant one in NLP so far which opens the era of pretrained language models (BERT, etc.).

Heuristics are good, and better heuristics are found every day. But is this the final picture of
how we improve our system? Are we just going to try to come up with new heuristics from our intuition, 

How are "good" heuristics found? Can we automate the processing of finding good "heuristic"?
