---
title: Survival Time Prediction of Metastatic Melanoma Patients by Computed Tomography using Convolutional Neural Networks
subtitle: Master Thesis ​(At EnCoV-TGI, Institut Pascal, Universite Clermont Auvergne, France, August 2020)
authors:
- Zakia Khatun

date: "2020-08-30"
#doi: "http://arxiv.org/abs/1810.00871"

# Schedule page publish date (NOT publication's date).


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
#publication: 	arXiv:1810.04637


abstract: 

# Summary. An optional shortened abstract.
summary: The main objective of this thesis was to study the prediction of the survival time of patients with metastatic melanoma in terms of 1-year survival as a binary classification. Dataset used in this study contains CTs of 71 patients with metastatic melanoma who were studied at Universite Clermont Auvergne Hospital. The number of lesions per patient varies from 1 to 11. To reach the objective, the survival time was anticipated using the accessible CT data as input of a 3D CNN. In this category, survival time was anticipated using full CT volumes and also from extracted 3D CT patches containing lesion regions. Here, the patches were extracted given the ground truth masks of the lesions. Moreover, segmentation of lesions coming from different organs was performed using two different 3D CNNs to examine the prediction of survival time based on newly extracted 3D CT patches. These new patches were extracted using our anticipated segmentation predicted masks of lesions. As the final test, it was also inspected whether aggregated deep segmentation feature map could help to predict survival time being an extra input channel to the CT data for 3D CNN or not. Our study showed that using aggregated deep segmentation feature map as an extra input channel to CT data came about in superior performance in survival time prediction compared to using as it were only 3D CT patches as input. In expansion, the prediction of survival time based on newly extracted 3D CT patches coming from our segmentation predicted masks was similar to the survival prediction using the 3D CT patches coming from ground truth masks.

tags:
- Survival Time Prediction
- Metastatic Melanoma
- Computed Tomography
- Lesion Segmentation, 
- Deep Segmentation Feature Maps
- Convolutional Neural Networks


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

Metastatic melanoma is a fatal disease with a poor prognosis and rapid systemic spread. Follow-up and study are imperative, especially within the early periods after diagnosis as the expected cure is seldom obtained after surgical excision and with adjuvant therapy. Typically, computed tomography (CT) scan contains a huge sum of data that ought to be completely analyzed and assessed by the radiologist or other healthcare proficient in a brief time. In this case, the CAD framework can be of extraordinary offer assistance as a moment supposition for experts. In spite of the fact that the CAD framework may play an imperative part in the analysis, small research has been published on the survival time prediction of metastatic melanoma based on the CAD system.


Our objective is to study the prediction of the survival time of patients with metastatic melanoma in terms of 1-year survival as a binary classification. Dataset used in this study contains CTs of 71 patients with metastatic melanoma who are studied at Universite Clermont Auvergne Hospital. The number of lesions per patient varies from 1 to 11. To reach the objective, the survival time is anticipated using the accessible CT data as input of a 3D CNN. In this category, survival time is anticipated using full CT volumes and also from extracted 3D CT patches containing lesion regions. Here, the patches are extracted given the ground truth masks of the lesions. Moreover, segmentation of lesions coming from different organs is performed using two different 3D CNNs to examine the prediction of survival time based on newly extracted 3D CT patches. These new patches are extracted using our anticipated segmentation predicted masks of lesions. As the final test, it is also inspected whether aggregated deep segmentation feature map can help to predict survival time being an extra input channel to the CT data for 3D CNN or not.


Our study shows that using aggregated deep segmentation feature map as an extra input channel to CT data comes about in superior performance in survival time prediction compared to using as it were only 3D CT patches as input. In expansion, the prediction of survival time based on newly extracted 3D CT patches coming from our segmentation predicted masks is similar to the survival prediction using the 3D CT patches coming from ground truth masks.


Further investigation of this study can be the addition of radiomic features with aggregated deep segmentation feature map as additional input to CT data besides experimenting on bigger dataset. Including clinical data such as age, sex, etc. can as well play a vital role.

