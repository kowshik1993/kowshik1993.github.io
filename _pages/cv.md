---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

Education
======
* M.S. in Cybersecurity, University of Nebraska at Omaha | Fall 2025 – Expected May 2027
* B.E. in Information Science and Engineering, Visvesvaraya Technological University | CGPA 3.68/4.00

Research Experience
======
* ASTRA Lab, University of Nebraska at Omaha | Research Assistant | Jan 2026 – Present
  * Authored and co-authored two research papers on robust audio watermarking, UAV acoustic sensing, and deep-learning-based audio processing.
  * Developed BOMark, a band-orthogonal multichannel audio-watermarking framework using parallel invertible neural networks and disjoint STFT frequency bands to improve       robustness, audio fidelity, watermark recovery, and tamper localization.
  * Developed an eight-channel audio preprocessing and U-Net-based spectral-separation pipeline to suppress UAV propeller noise and recover impulsive gunshot signatures from low-SNR recordings.
  * Implemented residual gunshot reconstruction and evaluated denoising performance using event-centered SNR heatmaps and spectrogram analysis across multiple rotor speeds, microphone positions, and source angles.
  * Contributed machine-learning methodology, model evaluation, technical figures, results interpretation, and manuscript preparation.
* ASTRA Lab, University of Nebraska at Omaha | Student Worker | Aug 2025 – Dec 2025
  * Implemented deep-learning-based audio feature extraction and baseline models
  * Developed and evaluated CNN, LSTM, ConvLSTM, RNN, and Transformer models for multi-class gunshot sound classification.
  * Built audio preprocessing and feature-extraction pipelines using segmented waveforms and log-Mel spectrograms.
  * Compared model performance through accuracy analysis, confusion matrices, and class-level evaluation.

Professional Experience
======
* TSTECH Bangladesh Limited | Assistant Manager | Oct 2022 – Jul 2025
  * Led network security audits and forensic readiness assessments across enterprise systems.
  * Maintained secure, high-availability Oracle-based systems supporting real-time production operations.
  * Owned ISO-based certification efforts and compliance documentation.
  * Drove access-control and awareness workflows.
* TSTECH Bangladesh Limited | Officer | Jan 2018 – Sep 2022
  * Built SQL-based analysis tools to detect anomalies and improve operational decision-making.
  * Ensure network security by configuring the devices and SOC application.
  * Managed server monitoring and intrusion-prevention controls.
  * Implemented RBAC and backup/recovery procedures.
* TSTECH Bangladesh Limited | Junior Officer | Jan 2017 – Dec 2017
  * Created automation scripts for audit preparation and performance monitoring.
  * Monitor windows server and applications running on the server.
  * Configure and maintain network equipments.
  * Maintained compliance documentation.

Grants
======
* Graduate Research and Creative Activity (GRACA) Award, University of Nebraska at Omaha
  * Funded research project on UAV-based acoustic monitoring and source tracking under severe drone ego-noise. ML-enabled noise reduction and robust localization of critical public-safety sounds in low-SNR conditions.

Skills
======
* Security & Forensics
  * Network auditing, risk mitigation, evidence handling, forensic readiness
* Programming & Scripting
  * Python, SQL, shell scripting, Arduino
* Databases
  * Oracle, Microsoft SQL Server
* Operating Systems
  * Windows Server, Linux, VMware
* Networking
  * CCNA-level networking, TCP/IP, wireless network configuration
* Modeling & Documentation
  * Excel VBA, SolidWorks, QMS documentation

Certifications
======
* Cisco Certified Network Administrator (CCNA)
* ISO 9001:2015 QMS Internal Auditor (SGS)
* ISO 9001:2015 QMS Documentation (SGS)
* Computer Aided Drafting and Design (CADD in SolidWorks)

Research Projects
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Achievements
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
