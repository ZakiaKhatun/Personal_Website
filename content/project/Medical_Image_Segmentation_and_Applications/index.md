---
title: To design, analyze and implement approaches for brain tissue segmentation
subtitle: Project of 'Medical Image Segmentation and Applications,' course  (​ Master's Third Semester at University of Girona, January 2020) 
authors:
- Zakia Khatun

date: "2020-01-16"
#doi: "http://arxiv.org/abs/1810.00871"

# Schedule page publish date (NOT publication's date).


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
#publication: 	arXiv:1810.04637


abstract: 

# Summary. An optional shortened abstract.
summary:  The main goal of this project is to develop tissue (WM, GM, and CSF) segmentation methods in brain MRI images. Dataset used is IBSR18 which contains 18 skull-stripped and bias field corrected T1-w images with different spatial resolutions (pixel spacing) and there is a heterogeneity in image intensities which hinders segmentation. System architecture- Data → Pre-processing → Segmentation. Steps- 1) Pre-processing (a) Normalization and Skull stripping of MNI template, b) Image Registration (We have used Elastix as a software to apply 3D registration of moving image on fixed), c) Histogram Stretching (The registered volumes’ histograms have been stretched which broadens the histogram of the image intensity levels, d) Histogram Matching (Histogram stretched output of IBSR 07 has been taken as reference to match all other volumes’ stretched histogram), and 2) Segmentation- 3D patch-wise segmentation using 3D U-Net.

tags:
- Brain tissue segmentation
- 3D U-net

featured: false

#url_pdf:
#url_code: 



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
  #caption: 'Skin Lesion Segmentation'
  #focal_point: ""
  #preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

The main goal of this project is to develop tissue (WM, GM, and CSF) segmentation methods in brain MRI images. Dataset used is IBSR18 which contains 18 skull-stripped and bias field corrected T1-w images with different spatial resolutions (pixel spacing) and there is a heterogeneity in image intensities which hinders segmentation. System architecture- Data → Pre-processing → Segmentation. Steps- 1) Pre-processing (a) Normalization and Skull stripping of MNI template, b) Image Registration (We have used Elastix as a software to apply 3D registration of moving image on fixed), c) Histogram Stretching (The registered volumes’ histograms have been stretched which broadens the histogram of the image intensity levels, d) Histogram Matching (Histogram stretched output of IBSR 07 has been taken as reference to match all other volumes’ stretched histogram), and 2) Segmentation- 3D patch-wise segmentation using 3D U-Net.
