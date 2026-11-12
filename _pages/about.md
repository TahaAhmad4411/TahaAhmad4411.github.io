---
permalink: /about/
title: "About Me"
author_profile: true
redirect_from: 
  - /about.html
---

I am a graduate researcher in **Computational Science and Engineering** at the National University of Sciences and Technology (NUST), SINES, Islamabad (MS expected January 2027). I work as a Research Scientist in the **Computational Biomechanics Lab** under Dr. Zartasha Mustansar.

My research sits where **medical imaging, deep learning and physics-based simulation** meet. My thesis looks at estimating **tumour-induced intracranial pressure (ICP) from routine MRI** with physics-informed neural networks. ICP is normally measured invasively, and my aim is a non-invasive, patient-specific estimate.

[Download my CV (PDF)](/files/Taha_Ahmad_Mirza_CV.pdf){: .btn .btn--primary}

Research Interests
======
* **Health AI**: rigorous, leakage-free evaluation of clinical machine-learning models
* **Brain tumour MRI analysis and segmentation** (BraTS, multi-parametric MRI)
* **Multimodal learning** for clinical prediction (imaging, clinical and genetic data)
* **Physics-informed machine learning** (PINNs and neural-network surrogates)
* **Patient-specific computational biomechanics** (FEA/CFD)

Current Research
======
**Non-invasive intracranial pressure estimation from MRI.** I am building an end-to-end pipeline:

MRI → tumour and ventricle segmentation → patient-specific 3D brain mesh → FEA/CFD simulation → neural-network surrogate

* Generated physics-based synthetic training data: 9 tumour-growth × CSF-obstruction scenarios per patient (~15k mesh nodes), at ~40 s per case on a laptop, run as a batch pipeline over 30+ MRI scans.
* Competed in the **BraTS 2025** glioma segmentation challenge with a 3D multi-class model on multi-parametric MRI (T1n, T1c, T2w, T2-FLAIR).
* Manuscript in preparation: *Patient-Specific Finite Element and CSF Flow Simulation of Tumour-Induced Intracranial Pressure from MRI.*

Previous Research
======
**Urdu-first crop advisory for cotton farmers** (AgriTech Project, SINES, NUST; PI: Dr. Absaar ul Jabbar, 2025). I built a Flask + GPT-4.1 RAG backend, an Android app and Urdu text-to-speech. The system turns live soil-sensor readings and weather forecasts into field-specific fertilizer and irrigation advice. A patent filing is in progress.

In a 189-query, 4-arm ablation, stage-specific rule thresholds gave **87.8%** fully correct advice, against 74.6% for full RAG and 5.3% for the LLM alone. I traced the drop under RAG to retrieval overriding the thresholds (exact McNemar test, *p* = 8 × 10⁻⁴).

Background
======
Before graduate school I spent over two years as a **Software Engineer at Afiniti** (2022–2025). There I analysed call data for 4.7M+ subscribers, which enabled $30K+ in monthly revenue recovery, and I tested AI products before deployment. I hold a **BS in Computer Science** from FAST-NUCES Islamabad (2022). I also teach: I have given 300+ hours of AI tutoring on Preply (4.6/5 rating) and was a Graduate TA for lab outreach programs.

News
======
* **2026**: Joined the Computational Biomechanics Lab, NUST, as Research Scientist.
* **2026**: Graduate TA for a 6-week AI internship in motion capture and rapid prototyping, and for the 9-day StemX AI event.
* **2025**: Research Impact Team Award, Dense Fusion (NUST SINES spin-off), selected from 20+ teams.
* **2025**: Competed in the BraTS 2025 glioma segmentation challenge.
