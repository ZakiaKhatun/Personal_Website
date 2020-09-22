---
title: To design, analyze and implement approaches for brain tissue segmentation
summary: The main goal of this project is to develop tissue (WM, GM, and CSF) segmentation methods in brain MRI images. Dataset used is IBSR18 which contains 18 skull-stripped and bias field corrected T1-w images with different spatial resolutions (pixel spacing) and there is a heterogeneity in image intensities which hinders segmentation. System architecture- Data → Pre-processing → Segmentation. Steps- 1) Pre-processing (a) Normalization and Skull stripping of MNI template, b) Image Registration (We have used Elastix as a software to apply 3D registration of moving image on fixed), c) Histogram Stretching (The registered volumes’ histograms have been stretched which broadens the histogram of the image intensity levels, d) Histogram Matching (Histogram stretched output of IBSR 07 has been taken as reference to match all other volumes’ stretched histogram), and 2) Segmentation- 3D patch-wise segmentation using 3D U-Net.
tags:
- PCA 
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
# publication_types: ["0"]



tags:
- PCA
featured: true


projects: []
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
The main goal of this project is to develop tissue (WM, GM, and CSF) segmentation methods in brain MRI images. Dataset used is IBSR18 which contains 18 skull-stripped and bias field corrected T1-w images with different spatial resolutions (pixel spacing) and there is a heterogeneity in image intensities which hinders segmentation. System architecture- Data → Pre-processing → Segmentation. Steps- 1) Pre-processing (a) Normalization and Skull stripping of MNI template, b) Image Registration (We have used Elastix as a software to apply 3D registration of moving image on fixed), c) Histogram Stretching (The registered volumes’ histograms have been stretched which broadens the histogram of the image intensity levels, d) Histogram Matching (Histogram stretched output of IBSR 07 has been taken as reference to match all other volumes’ stretched histogram), and 2) Segmentation- 3D patch-wise segmentation using 3D U-Net.
