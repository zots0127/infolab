---
title: Automatic Diabetic Retinopathy Grading System Based on Detecting Multiple
  Retinal Lesions
publication_types:
  - "2"
authors:
  - Eman Abdelmaksoud
  - Shaker El-Sappagh
  - Sherif Barakat
  - Tamer Abuhmed
  - Mohammed Elmogy
date: "2021-01-19T00:00:00Z"
doi: 10.1109/ACCESS.2021.3052870
publication: "*IEEE Access 9, 15939-15960"
abstract: Multi-label classification (MLC) is considered an essential research subject in the computer vision field, principally in medical image analysis. For this merit, we derive benefits from MLC to diagnose multiple grades of diabetic retinopathy (DR) from various colored fundus images, especially from multi-label (ML) datasets. Therefore, ophthalmologists can detect early signs of DR as well as various grades to initiate appropriate treatment and avoid DR complications. In this paper, we propose a comprehensive ML computer-aided diagnosis (CAD) system based on deep learning technique. The proposed system's main contribution is to detect and analyze various pathological changes accompanying DR development in the retina without injecting the patient with dye or making expensive scans. The proposed ML-CAD system visualizes the different pathological changes and diagnoses the DR grades for the ophthalmologists. First, we eliminate noise, enhance quality, and standardize the sizes of the retinal images. Second, we differentiated between the healthy and DR cases by calculating the gray level run length matrix average in four different directions. The system automatically extracts the four changes: exudates, microaneurysms, hemorrhages, and blood vessels by utilizing a deep learning technique (U-Net). Next, we extract six features, which are the gray level co-occurrence matrix, areas of the four segmenting pathology variations, and the bifurcation points count of the blood vessels. Finally, the resulting features were afforded to an ML support vector machine (SVM) based on a classifier chain to differentiate the various DR grades. We utilized eight benchmark datasets (four of them are considered ML) and six different performance evaluation metrics to evaluate the proposed system's performance. It achieved 95.1%, 91.9%, 86.1%, 86.8%, 84.7%, 86.2% for accuracy, area under the curve, sensitivity, specificity, positive predictive value, and dice similarity coefficient, respectively. The experiments show encouraging results as compared with other systems.
draft: false
featured: false
url_pdf: https://infolab.skku.edu/publication/09328438.pdf
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-04-29T04:24:47.523Z
---
