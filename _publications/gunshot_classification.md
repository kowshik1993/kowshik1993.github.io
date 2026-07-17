---
title: "A Comparative Study of Convolutional, Recurrent, and Transformer Architectures with a Parameter-Efficient Patch Transformer"
collection: publications
category: conferences
permalink: /publication/gunshot_classification
excerpt: "A comparative study of convolutional, recurrent, and transformer architectures for fine-grained firearm identification from gunshot acoustic signatures."
date: 2026-07-17
venue: "Completed manuscript; planned for submission to a peer-reviewed conference"
citation: "K. Chowdhury and P. Jiang, 'A Comparative Study of Convolutional, Recurrent, and Transformer Architectures with a Parameter-Efficient Patch Transformer,' unpublished manuscript, 2026."
---

This manuscript presents a comparative study of six deep-learning architectures for identifying specific firearms from their gunshot acoustic signatures. The evaluated models include a transfer-learned PANNs CNN14, bidirectional LSTM, ConvLSTM, fine-tuned Audio Spectrogram Transformer, knowledge-distilled compact Transformer, and a proposed parameter-efficient audio Patch Transformer.

The study uses an 18-class gunshot audio-forensics dataset and compares the models using classification accuracy, macro-F1 score, confusion matrices, training behavior, parameter count, and t-SNE visualization of learned feature embeddings. A content-level audit was also conducted to identify train-test data leakage and provide a more reliable evaluation.

The proposed Patch Transformer processes log-Mel spectrograms as non-overlapping time-frequency patches and uses a compact six-layer Transformer encoder. It achieved the highest held-out test accuracy of **74.7%** under a fully leakage-free evaluation while using approximately **5.8 million parameters**. This is substantially fewer than the approximately 80–86 million parameters used by the CNN14 and Audio Spectrogram Transformer baselines.

The results indicate that the compact Patch Transformer provides a promising balance of classification accuracy, computational efficiency, and evaluation reliability for forensic analysis, public-safety acoustic monitoring, and edge-based firearm-identification systems.

**Status:** Manuscript completed; not yet submitted.
