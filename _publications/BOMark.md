---
title: "Watermarks That Survive: Band-Orthogonal Multi-Channel Audio Watermarking"
collection: publications
category: manuscripts
permalink: /publication/BOMark
excerpt: "BOMark is a band-orthogonal multichannel audio-watermarking framework designed to provide robust watermark recovery, high audio fidelity, and tamper localization under common signal-processing attacks."
date: 2026-07-17
venue: "Completed manuscript; intended for submission to the Network and Distributed System Security Symposium (NDSS)"
citation: "K. Chowdhury and P. Jiang, 'Watermarks That Survive: Band-Orthogonal Multi-Channel Audio Watermarking,' unpublished manuscript, 2026."
---

This manuscript presents **BOMark**, a Band-Orthogonal Multi-Channel Audio Watermarking framework for copyright protection, media authentication, and audio provenance verification. BOMark partitions the short-time Fourier transform (STFT) spectrum into non-overlapping frequency bands and uses parallel invertible neural network encoder-decoder branches to embed independent watermark streams without cross-band interference.

The framework provides a configurable trade-off among watermark capacity, robustness, redundancy, and audio fidelity. Its multiband structure also supports band-level recovery and tamper localization when portions of the audio spectrum are removed or damaged.

BOMark was evaluated against four single-stream audio-watermarking baselines—WavMark, IDEAW, Timbre, and AudioSeal—under common distortions including additive noise, compression, filtering, resampling, quantization, echo, and time stretching. At a 256-bit embedding budget, BOMark achieved a mean bit accuracy of **0.997** across the evaluated attacks, compared with **0.972** for WavMark, while maintaining an embedding SNR of **39.9 dB**. The framework was also evaluated using over-the-air recordings captured with a 16-microphone UMA-16 array.

**Status:** Manuscript completed; not yet submitted.
