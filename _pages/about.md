---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
colorlinks: true
redirect_from: 
  - /about/
  - /about.html
---

I am a doctoral candidate in the Electrical and Computer Engineering, Clarkson University. Currently, I am working in [Communications, Signal Processing, Networking Lab (CoSiNe Lab)](https://cosine.clarkson.edu/), advised by
[Prof. Mahesh Banavar](https://webspace.clarkson.edu/~mbanavar/wordpress/) and working closely with [Prof. Jie Sun](https://sites.google.com/view/jiesun/home) and [Prof. Stephanie Schuckers](https://www.clarkson.edu/people/stephanie-schuckers). 
My research focuses on applying concepts from machine learning, computer vision to develop algorithms to solve problems in fields related to biometrics and localization. My work has resulted in papers and presentations at conferences and symposiums (see resume for details).

If you are interested in knowing more about my research, please get in touch!

# Projects:

## 1. Designing a skin reflectance measure to mitigate bias across demographics in Face recognition

Face recognition (FR) systems are fast becoming ubiquitous. However, differential performance among certain demographics was identified in several widely used FR models. The skin tone of the subject is an important factor in addressing the differential performance. Previous work has used modeling methods to propose skin tone measures of subjects across different illuminations or utilized subjective labels of skin color and demographic information. However, such models heavily rely on consistent background and lighting for calibration, or utilize labeled datasets, which are time-consuming to generate or are unavailable. In this work, we have developed a novel and data-driven skin color measure capable of accurately representing subjects' skin tone from a single image, without requiring a consistent background or illumination. Our measure leverages the dichromatic reflection model in RGB space to decompose skin patches into diffuse and specular bases. 

## 2. Multi-user classification from keystroke data

Multi-user authentication from keystroke data is an open problem that needs to be solved. When an online account or a common desktop is shared among multiple users, there is a need to determine who the current user is at log-in. In this paper, a non-linear feature transformation-based multi-user classification algorithm is proposed. Quantile transformation is proposed to map raw keystroke features to a uniform distribution to limit outliers. Then, dimensionality reduction techniques such as PCA, Kernel-PCA, and t-SNE are applied to the transformed features to project into reduced feature space. Unsupervised clustering algorithms such as DB-SCAN and GMM are applied in the reduced feature space to identify the number of users accessing the system. Using these results, a k-nearest neighbor search algorithm is used, in conjunctions with labeled clusters to classify users. The algorithm is validated using the CMU keystroke benchmark dataset. Once we identify the number of users, we can successfully classify users with an accuracy of over 93 percent. 

