---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download full CV (PDF)](/files/Taha_Ahmad_Mirza_CV.pdf){: .btn .btn--primary}

Education
======
* **M.S. in Computational Science and Engineering**, NUST (SINES), Islamabad, Jan 2025 – Jan 2027 (expected)
  * Thesis: *Patient-Specific Estimation of Tumour-Induced Intracranial Pressure from MRI using Physics-Informed Neural Networks*
  * Supervisor: Dr. Zartasha Mustansar
  * GPA: 3.50/4.00 (3.67 in last semester)
  * Coursework: Machine Learning, Deep Learning, Large Language Models, Health AI, Data Analysis and Statistics
* **B.S. in Computer Science**, FAST National University of Computer and Emerging Sciences (NUCES), Islamabad, June 2022
  * Coursework: Data Structures and Algorithms, Artificial Intelligence, Calculus, Probability and Statistics

Research Experience
======
* **Research Scientist**, Computational Biomechanics Lab, NUST. Jan 2026 – Present (PI: Dr. Zartasha Mustansar)
  * Building an end-to-end intracranial pressure (ICP) pipeline: MRI → tumour and ventricle segmentation → patient-specific 3D brain mesh → FEA/CFD simulation → neural-network surrogate. ICP is normally measured invasively; the aim is a non-invasive estimate from routine MRI.
  * Generated physics-based synthetic training data: 9 tumour-growth × CSF-obstruction scenarios per patient (~15k mesh nodes) in ~40 s per case on a laptop, built as a batch pipeline for 30+ MRI scans.
  * Competed in the BraTS 2025 glioma segmentation challenge, training a 3D multi-class model on multi-parametric MRI (T1n, T1c, T2w, T2-FLAIR).

* **Research Assistant**, AgriTech Project, SINES, NUST. Jan 2025 – Dec 2025 (PI: Dr. Absaar ul Jabbar)
  * Built an Urdu-first crop advisory system for cotton farmers (Flask + GPT-4.1 RAG backend, Android app, Urdu text-to-speech) that turns live soil-sensor readings and weather forecasts into field-specific fertilizer and irrigation advice; patent filing in progress.
  * Ran a 189-query, 4-arm ablation: stage-specific rule thresholds reached 87.8% fully correct advice vs. 74.6% for full RAG and 5.3% for the LLM alone; traced the −13.2 pp drop to retrieval overriding the thresholds (exact McNemar test, *p* = 8 × 10⁻⁴).
  * Designed rule-based soil classification (growth-stage NPK limits, USDA salinity classes for EC) and 5-day forecast rules for rain and heat stress, served via Flask REST APIs with Firestore sync at < 90 s end-to-end response.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Selected Projects
======
* **Multimodal Alzheimer's Progression Prediction** (Video Vision Transformers, TensorFlow). [Code](https://github.com/TahaAhmad4411/Alzheimer-s-Disease-Classifier)
  * Multimodal pipeline over 487 longitudinal 3D T1 MRI scans (227 subjects) from ADNI, plus clinical, demographic and APOE/TOMM40 genetic data.
  * Audited an earlier pipeline reporting 81% accuracy and found subject-level data leakage, test-set reuse and label circularity; rebuilt it with subject-level splits, baselines and bootstrap confidence intervals.
* **Stable Diffusion Web App** (TensorFlow, Streamlit). [Code](https://github.com/TahaAhmad4411/Generate-Image-using-Diffusion-Models)
* **Data Collection and Training GPT-2** (GPT-2, BeautifulSoup). [Code](https://github.com/TahaAhmad4411/Dataset-Collection-and-Pretraining-of-GPT-2-LM-from-Scratch)
* **HateSpeechInspector** (Python, XLNet, React, PyTorch). [Code](https://github.com/HSInspector/HateSpeechInspector/tree/main)
* **Breast Tumor Classification Using Data Analysis** (feature selection, hypothesis testing, Random Forest): 98% accuracy after reducing 32 features to 3.

Industry Experience
======
* **AI Product Engineer**, Latin American Farms, Canada (Remote). 2025 – Present
  * Scaling up a sensor-based monitoring system for soil moisture and temperature.
  * Built a Flutter app with a Python backend for real-time data visualization.
* **Software Engineer I**, Afiniti, Islamabad. Nov 2022 – Jan 2025
  * Analyzed call data (4.7M+ subscribers) using SQL, Python, and Excel to identify root causes, enabling $30K+ monthly revenue recovery.
  * Built a Python tool to automate analysis of call logs, call statistics, sequence diagrams, and error detection.
  * Performed unit, feature, UAT, and integration testing of Afiniti products before AI-based model deployment.
* **Intern**, Open AIMP (Remote). Sept 2021 – Dec 2021
  * Implemented Spark-based data streaming for analytics pipelines, cutting reporting delays from hours to minutes.

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors and Certifications
======
* **Research Impact Team Award**, Dense Fusion (NUST SINES spin-off), selected from 20+ teams, 2025
* **AWS Certified Cloud Practitioner**

Technical Skills
======
* **Languages:** Python, Bash, SQL
* **ML and Data:** PyTorch, TensorFlow, Hugging Face Transformers, RAG, OpenAI API
* **Medical Imaging:** multi-parametric MRI, NIfTI, nnU-Net, 3D Slicer
* **Research Methods:** medical image segmentation, FEA/CFD simulation, PINNs, ablation studies, significance testing
* **Tools:** Docker, Flask, Firebase/Firestore, Git

References
======
* **Dr. Zartasha Mustansar**: Tenured Associate Professor, SINES, NUST. Thesis Supervisor; PI, Computational Biomechanics Lab
* **Dr. Muhammad Tariq Saeed**: HoD SINES and Associate Professor, NUST. Course Instructor, ML and Deep Learning
* **Dr. Absaar ul Jabbar**: Associate Professor, SINES, NUST. PI, AgriTech Project
* **Dr. Muhammad Qasim**: Associate Professor, SINES, NUST. Course Instructor, Data Analysis and Statistics

Contact details for references are listed in the [PDF CV](/files/Taha_Ahmad_Mirza_CV.pdf).
