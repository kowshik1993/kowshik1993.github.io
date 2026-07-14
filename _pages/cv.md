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
* M.S. in Cybersecurity, University of Nebraska at Omaha (UNO), Fall 2025 – Expected May 2027
* B.E. in Information Science and Engineering, Visvesvaraya Technological University, CGPA 3.68/4.00

Research Experience
======
* Jan 2026 – May 2026: Research Assistant, UAV Audio Sensing
  * ASTRA Lab, University of Nebraska at Omaha
  * Trained/evaluated a model to suppress propeller noise and recover surrounding audio
  * Benchmarked DoA estimation accuracy and stability using UMA-16 microphone array
  * Integrated noise reduction with UMA-16 tracking on a hovering drone; tested reliability using controlled playback, including simulated gunshot audio
* Aug 2025 – Dec 2025: Student Worker, UAV Audio Research
  * ASTRA Lab, University of Nebraska at Omaha
  * Supported drone ego-noise detection and acoustic source localization experiments for UAV-based gunshot event awareness
  * Implemented deep-learning-based audio feature extraction and baseline models

Professional Experience
======
* Oct 2022 – Jul 2025: Assistant Manager
  * TSTECH Bangladesh Limited
  * Led network security audits and forensic readiness assessments across enterprise systems
  * Maintained secure, high-availability Oracle-based systems supporting real-time production operations
  * Owned ISO-based certification efforts and compliance documentation; drove access-control and awareness workflows
* Jan 2018 – Sep 2022: Officer, IT
  * TSTECH Bangladesh Limited
  * Built SQL-based analysis tools to detect anomalies and improve operational decision-making
  * Managed server monitoring and intrusion-prevention controls; implemented RBAC and backup/recovery procedures
* Jan 2017 – Dec 2017: Junior Officer, IT
  * TSTECH Bangladesh Limited
  * Created automation scripts for audit preparation and performance monitoring; maintained compliance documentation

Grants
======
* Graduate Research and Creative Activity (GRACA) Award, University of Nebraska at Omaha
  * Funded UAV-based acoustic monitoring and source tracking under severe drone ego-noise: ML-enabled noise reduction and robust localization of critical public-safety sounds in low-SNR conditions

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
* CCNA
* ISO 9001:2015 QMS Internal Auditor (SGS)
* ISO 9001:2015 QMS Documentation (SGS)
* CADD (SolidWorks)

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
