---
title: "Machine Learning–Based Detection of External Gunshot Sound Sources in Propeller Acoustic Near Field"
collection: publications
category: conferences
permalink: /publication/VFS_drone_ego_noise_suppression_for_gunshot_detection
excerpt: "A machine-learning-assisted study of detecting and recovering external gunshot signatures masked by strong UAV propeller noise."
date: 2026-05-05
venue: "Vertical Flight Society’s 82nd Annual Forum & Technology Display, West Palm Beach, Florida, USA"
citation: "G. E. Sian-Bates, S. K. Li, K. Chowdhury, and P. Jiang, 'Machine Learning–Based Detection of External Gunshot Sound Sources in Propeller Acoustic Near Field,' presented at the Vertical Flight Society’s 82nd Annual Forum & Technology Display, West Palm Beach, Florida, May 5–7, 2026."
---

This paper investigates the detectability of external gunshot sounds under strong UAV propeller noise using multichannel acoustic recordings collected across different rotor speeds, microphone positions, source angles, and propagation distances. The study combines acoustic analysis with a machine-learning-based spectral-separation framework designed to suppress propeller-related components and improve the visibility of impulsive gunshot signatures.

My contribution focused on the machine-learning component conducted at the ASTRA Lab, University of Nebraska at Omaha. I developed the multichannel audio preprocessing pipeline, including STFT-based time-frequency representation, ambient-profile subtraction, and temporal segmentation. I also designed and evaluated a U-Net-based propeller-noise suppression model that estimates the propeller spectral component and reconstructs the residual gunshot signature. Model performance was analyzed using event-centered SNR heatmaps and representative spectrograms across 3000, 4000, and 5000 RPM conditions.
