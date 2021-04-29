---
title: "Intensive Care Unit Mortality Prediction: An Improved Patient-Specific
  Stacking Ensemble Model"
publication_types:
  - "2"
authors:
  - Nora El-Rashidy
  - Shaker El-Sappagh
  - Tamer Abuhmed
  - Samir Abdelrazek
  - Hazem M El-Bakry
date: "2020-07-20T00:00:00Z"
doi: 10.1109/ACCESS.2020.3010556.
publication: "IEEE Access 8, 133541-133564"
abstract: The intensive care unit (ICU) admits the most seriously ill patients requiring extensive monitoring. Early ICU mortality prediction is crucial for identifying patients who are at great risk of dying and for providing suitable interventions to save their lives. Accordingly, early prediction of patients at high mortality risk will enable their provision of appropriate and timely medical services. Although various severity scores and machine-learning models have recently been developed for early mortality prediction, such prediction remains challenging. This paper proposes a novel stacking ensemble approach to predict the mortality of ICU patients. Our approach is more accurate and medically intuitive compared to the literature work. Data were prepared and feature selection was processed under the supervision of the ICU domain expert. The data were split into six modalities based on the expert's decisions. For the prediction process, a separate classifier was selected for each modality based on the performance of the classifiers. We utilized the most popular and diverse classifiers in the literature, including linear discriminant analysis, decision tree (DT), multilayer perceptron, k-nearest neighbor, and logistic regression (LR). Then, a stacking ensemble classifier was constructed and optimized based on the fusion of these five classifier decisions. The framework was evaluated using 10,664 patients from the medical information mart for intensive care (MIMIC III) benchmark dataset. To predict patient mortality, extensive experiments were conducted using the patients' time series data of different lengths. For each patient, the first 6, 12, and 24 hours of the first stay were tested. The results indicate that our model outperformed the state-of-the-art approaches in terms of accuracy (94.4%), F1 score (93.7%), precision (96.4%), recall (91.1%), and area under the receiver operator characteristic (ROC) curve (93.3%). These results demonstrate the ability and efficiency of our approach to predict ICU mortality.
draft: false
featured: false
url_pdf: https://infolab.skku.edu/publication/09144577.pdf
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-04-29T04:28:53.099Z
---
