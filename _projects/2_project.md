---
layout: page
title: Reading Noisy Captions Embedded in Images
description: Encoder-Decoder network for extracting text from images using attention-based LSTM
img:
importance: 2
category: work
---

Developed an Encoder-Decoder network for extracting text captions embedded within images, even under noisy conditions. The encoder uses ResNet-50 for robust image feature extraction, and the decoder employs an attention-based LSTM to focus on relevant image regions during text generation.

**Key contributions:**

- ResNet-50 based encoder for visual feature extraction
- Attention-based LSTM decoder for text generation
- Teacher forcing for stable training
- Beam search for improved prediction at inference
- BLEU score evaluation for caption quality
