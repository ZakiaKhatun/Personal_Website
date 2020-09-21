---
title: Breast Mass Detection using Machine Learning algorithm
summary:  The main aim of this project was to design a Computer Aided Diagnosis system which can detect mass/masses in mammograms to help the screening procedure. System architecture- Image → Candidate extraction → Feature extraction → Classification. Steps- 1) Candidate extraction- Histogram equalization → Multiple thresholding → Selection of n best threshold using mean and variance → Selection of desired threshold based on chosen threshold. 2) Feature extraction- Three types of features used are shape, texture (Haralick) and Intensity features. 3) Classification- Different type of classifiers were tested both individually and as a cascade of two or more to evaluate performance. At the end, the voting between Gaussian Naïve Bayes and Logistic regression was used where this voting is an AND combination of two classifiers.
tags:
- Machine Learning 
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
# publication_types: ["0"]



tags:
- Machine Learning
featured: true


projects: []
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

The main aim of this project was to design a Computer Aided Diagnosis system which can detect mass/masses in mammograms to help the screening procedure. System architecture- Image → Candidate extraction → Feature extraction → Classification. Steps- 1) Candidate extraction- Histogram equalization → Multiple thresholding → Selection of n best threshold using mean and variance → Selection of desired threshold based on chosen threshold. 2) Feature extraction- Three types of features used are shape, texture (Haralick) and Intensity features. 3) Classification- Different type of classifiers were tested both individually and as a cascade of two or more to evaluate performance. At the end, the voting between Gaussian Naïve Bayes and Logistic regression was used where this voting is an AND combination of two classifiers.
