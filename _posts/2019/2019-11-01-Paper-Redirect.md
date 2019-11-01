---
layout: post
title: Paper Redirect
---

Detecting Depression from Voice

Dataset: [AVEC 2013](https://avec2013-db.sspnet.eu/) & AVEC 2017\
AVEC 2013: subset of AVDLC, 300 recordings.\
Labelled with depression score in 21 items BDI-Ⅱ scale ranging from 0-63, depressed: > 19, mean: 15,3, standard deviation: 12.3.\
AVEC 2017: DSC dataset, 189 audio recordings, labelled with 8 items PHQ-8 ranging 0-24, depressed: >= 10, mean 6.67, standard deviation: 5.75.\
Binary classification: distinguish depressed fron non-depressed.\
Regression problem: score depression severity.\
Audio based depression detection system from phone conversation.\
\
Data preprocess: long audio segmentation, low-level descriptors features.\
Model Training (both classification and regression): Random Forest, Support Vector Machine (SVM), Gradient Boosting Tree (GBT), Deep Neural Network.