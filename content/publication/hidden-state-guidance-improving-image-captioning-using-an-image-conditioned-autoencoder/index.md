---
title: "Hidden State Guidance: Improving Image Captioning using An Image
  Conditioned Autoencoder"
publication_types:
  - "1"
authors:
  - Jialin Wu and Raymond J. Mooney
publication_short: NeurIPS 2019 Vigil Workshop
abstract: Most RNN-based image captioning models receive supervision on the
  output words to mimic human captions. Therefore, the hidden states can only
  receive noisy gradient signals via layers of back-propagation through time,
  leading to less accurate generated captions. Consequently, we propose a novel
  framework, Hidden State Guidance (HSG), that matches the hidden states in the
  caption decoder to those in a teacher decoder trained on an easier task of
  autoencoding the captions conditioned on the image. During training with the
  REINFORCE algorithm, the conventional rewards are sentence-based evaluation
  metrics equally distributed to each generated word, no matter their relevance.
  HSG provides a word-level reward that helps the model learn better hidden
  representations. Experimental results demonstrate that HSG clearly outperforms
  various state-of-the-art caption decoders using either raw images or detected
  objects as inputs.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2019-12-06T19:31:30.353Z
---
