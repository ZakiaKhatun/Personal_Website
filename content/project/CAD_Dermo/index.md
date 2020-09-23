---
title: Developing Computer Aided Algorithm for the diagnosis in Dermoscopic images to classify melanoma vs all other types using deep learning approach
subtitle: Project of 'Computer Aided Diagnosis' course  (​ Master's Third Semester at University of Girona, January 2020) 
authors:
- khrystyna Faryna
- Zakia Khatun
- Nur Adhianti

date: "2020-01-08"
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
summary:  The main goal of this project was to design a Computer Aided Diagnosis system to classify dermoscopic images whether any case belongs to Nevus or lesion. System architecture- Image → Normalization → Per instance standardization → Aggressive Data Augmentation → Classification. Steps- 1) Data normalization, 2) Per instance standardization (Standardization by mean and std of the training dataset), 3) Aggressive Data Augmentation (Rotation, Width and Height shift, Zooming, Flipping, Brightness), 4) Classification; Best performing classification model- Ensemble of Inception ResNetv2, Inception v3, EfficientNet B3 (ImageNet-pretrained).
tags:
- Computer Aided algorithm
- Dermoscopic images

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

The main goal of this project was to design a Computer Aided Diagnosis system to classify dermoscopic images whether any case belongs to Nevus or lesion. System architecture- Image → Normalization → Per instance standardization → Aggressive Data Augmentation → Classification. Steps- 1) Data normalization, 2) Per instance standardization (Standardization by mean and std of the training dataset), 3) Aggressive Data Augmentation (Rotation, Width and Height shift, Zooming, Flipping, Brightness), 4) Classification; Best performing classification model- Ensemble of Inception ResNetv2, Inception v3, EfficientNet B3 (ImageNet-pretrained).
