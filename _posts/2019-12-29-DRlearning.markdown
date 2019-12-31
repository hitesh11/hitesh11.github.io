---
layout: post
title:  "Semi-supervised learning for Diabetic Retinopathy"
date:   2019-12-29 18:00:00 +00:00
image: /images/Screen_DR_Architecture.jpg
categories: research
advisor: Prof. Asim Smailagic
advisor_link: https://www.cs.cmu.edu/~./asim/
report: /pdfs/Semi_supervised_learning_for_Diabetic_Retinopathy_Report.pdf

---
Built a semi-supervised deep learning pipeline for Diabetic Retinopathy (DR) detection from retinal fundus images to address the lack of labeled images in the medical domain. Designed a novel deep learning architecture to enable simultaneous training of auto-encoder and classifier networks to learn useful latent representation from unlabelled data. Extended the [GradNorm](https://arxiv.org/pdf/1711.02257.pdf)  algorithm to handle dynamic tuning of gradient magnitudes of multiple losses in semi-supervised multi-task settings, where some of the losses may not be present for all data samples. Achieved an improvement of 2% on ResNet18 baseline on the [Messidor DR dataset](http://www.adcis.net/en/third-party/messidor/), and are currently working towards evaluating performance on larger datasets such as [EyePACS](http://www.eyepacs.com/data-analysis) and publishing our work.
