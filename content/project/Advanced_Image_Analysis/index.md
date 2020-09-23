---
title: Breast Mass Detection using Machine Learning algorithm
subtitle: Project of 'Pattern Recognition and Machine Learning' course  (​ Master's Second Semester at University of Cassino, June 2019) 
authors:
- Isaac Llorente
- Zakia Khatun
- Pierpaollo Vendetelli

date: "2019-06-14"
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
summary: The main aim of this project was to design a Computer Aided Diagnosis system which can detect mass/masses in mammograms to help the screening procedure. System architecture- Image → Candidate extraction → Feature extraction → Classification. Steps- 1) Candidate extraction- Histogram equalization → Multiple thresholding → Selection of n best threshold using mean and variance → Selection of desired threshold based on chosen threshold. 2) Feature extraction- Three types of features used are shape, texture (Haralick) and Intensity features. 3) Classification- Different type of classifiers were tested both individually and as a cascade of two or more to evaluate performance. At the end, the voting between Gaussian Naïve Bayes and Logistic regression was used where this voting is an AND combination of two classifiers.
tags:
- Machine Learning
- Python 

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

The main aim of this project was to design a Computer Aided Diagnosis system which can detect mass/masses in mammograms to help the screening procedure. System architecture- Image → Candidate extraction → Feature extraction → Classification. Steps- 1) Candidate extraction- Histogram equalization → Multiple thresholding → Selection of n best threshold using mean and variance → Selection of desired threshold based on chosen threshold. 2) Feature extraction- Three types of features used are shape, texture (Haralick) and Intensity features. 3) Classification- Different type of classifiers were tested both individually and as a cascade of two or more to evaluate performance. At the end, the voting between Gaussian Naïve Bayes and Logistic regression was used where this voting is an AND combination of two classifiers.


