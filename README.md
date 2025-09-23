# Gemma3 from scratch

## BACKGROUND:

    This repository tracks my journey of learning the recent advancements in a popular Small Language Models (SMLs) called Gemma3. This repo is a work in progress and will be updated frequently as I continue to learn the concepts in LLM architectures in detail.

    The original architecture of the Gemma3 model is given as an image in this same repo. I try to come play with some parameters in the architecture, so the final parameter count need not be same as expected (~270M) and will be around 50-70 million parameters.


## Basic architecture summary:

    As shown in the image, Gemma3 model stick to most common aspects in modern LLM architectures like RMS norm, RoPE (for positional embeddings), Feed forward neural networks (FFNN). In addition, they also implement a combination of Sliding window attention and full causal attention mechanisms. They also implement a number of normalization steps (like QK norm and RMS-norm), the most prevalent being the RMS-Norm steps spread throughtout the architecture. 

    While I stick to overall architecture, I have tried to modify certain sections of the architecture to play with and learn the details. I will be updating my learnings too in the repo in the future. 

## NOTE:

    Due to constraints in compute resources, I am unable to pre-train the model with large corpus of data, as the Google colab instances of GPU (T4) only allow for limited timeframe of operation per day. Thus, the inferences are expected to not be coherent.

## Bibliography:

    I would also like to thank popular research groups like Vizuara and Sebastian Raschka for their solid tutorials on basics of LLMs and architecture coding resoruces.
