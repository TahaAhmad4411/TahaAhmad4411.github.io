---
title: "Multimodal Alzheimer's Progression Prediction"
excerpt: "Video Vision Transformers over 487 longitudinal 3D MRI scans from ADNI, with clinical, demographic and genetic data, plus an audit that uncovered data leakage in an earlier pipeline."
collection: portfolio
---

**Stack:** Video Vision Transformers, TensorFlow · [GitHub repository](https://github.com/TahaAhmad4411/Alzheimer-s-Disease-Classifier)

* Built a multimodal pipeline over **487 longitudinal 3D T1 MRI scans (227 subjects)** from ADNI. Each scan is linked to the clinical visit nearest in time (median gap 5 days), together with demographic and APOE/TOMM40 genetic data.
* **Audited and corrected an earlier pipeline** that reported 81% accuracy. I found three problems:
  * subject-level data leakage (487 scans inflated to 1,212 samples)
  * the test set being reused for early stopping
  * label circularity from cognitive-score inputs
* Rebuilt the pipeline with **subject-level splits, baselines and bootstrap confidence intervals**.
