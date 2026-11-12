---
title: "Urdu-First Crop Advisory System"
excerpt: "A Flask + GPT-4.1 RAG backend with an Android app and Urdu text-to-speech that turns soil-sensor and weather data into fertilizer and irrigation advice for cotton farmers. A 4-arm ablation showed rule thresholds beating full RAG. Patent filing in progress."
collection: portfolio
---

**Stack:** Flask, GPT-4.1, RAG, Android, Firebase/Firestore, Urdu TTS · AgriTech Project, SINES, NUST

* Turns live soil-sensor readings and weather forecasts into field-specific fertilizer and irrigation advice in Urdu.
* **189-query, 4-arm ablation:** stage-specific rule thresholds gave 87.8% fully correct advice, against 74.6% for full RAG and 5.3% for the LLM alone. The −13.2 pp drop under RAG came from retrieval overriding the thresholds (exact McNemar test, *p* = 8 × 10⁻⁴).
* Rule-based soil classification (growth-stage NPK limits, USDA salinity classes for EC) and 5-day forecast rules for rain and heat stress, served through Flask REST APIs with < 90 s end-to-end response.
