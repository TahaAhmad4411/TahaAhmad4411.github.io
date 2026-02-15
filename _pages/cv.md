---
layout: archive
title: "CV"
permalink: /CV/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computational Science and Engineering, NUST Islamabad, 2026
* B.S. in Computer Science, FAST NUCES Islamabad, 2022

Work experience
======
* NUST
  Machine Learning Research Engineer. Islamabad, Pakistan . 2025-Present  
  * Owned the integration of the embedded controller systems with the Android application to generate the reommendations.
  * Implemented an LLM-driven decision pipeline that analyzes sensor and soil data, retrieves agronomic actions via FAISS, and generates context-aware recommendations.
  * Built multilingual support with automated English → Urdu and English → Spanish translation and voice synthesis, enabling farmer-friendly, accessible guidance.
  * Improved crop advisory accuracy by 20% using a custom RAG pipeline with FAISS, Sentence Transformers, domain-tuned Agri-BERT, English-to-Urdu TTS.
  * Integrated Flask REST APIs with Android and Firebase using POST requests for real-time data sync and inference delivery, achieving < 30 seconds end-to-end response time, with APIs, and storage/retrieval in Firestore.

* Afiniti Software Solutions .
  Software Engineer. Islamabad, Pakistan . 2022-2025
  * Owned SQL-based analysis over 4.7M+ subscriber transactional datasets, identifying revenue leakage and operational failures
  * Built reusable SQL queries and analytical workflows to validate KPIs used by business and engineering teams
  * Delivered root-cause analyses that directly enabled $30K+ monthly revenue recovery

* Open AIMP .
  AI Intern. Remote . 2021 
  * Cut reporting delays from hours to minutes by implementing Spark-based data streaming.
  * Enhanced analytics pipelines by executing Spark-based streaming data transfer.
  
Technical Skills
======
* Languages
  * Python, Bash, C++
* Machine Learning
  * Pytorch, HuggingFace, Langchain, Langraph
* Automation
  * N8n, AgentBuilder OpenAI
* Systems
  * CUDA, Docker, Kubernetees, Firebase, Cloudinary

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
