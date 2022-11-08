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

Currently, I work as a computer vision research scientist at Thales DIS USA,Inc. Before that, I graduated with a Ph.D. in the Electrical and Computer Engineering from Clarkson University.  I worked in [Communications, Signal Processing, Networking Lab (CoSiNe Lab)](https://cosine.clarkson.edu/), advised by
[Prof. Mahesh Banavar](https://webspace.clarkson.edu/~mbanavar/wordpress/) and worked closely with [Prof. Stephanie Schuckers](https://www.clarkson.edu/people/stephanie-schuckers) and [Prof. Jie Sun](https://sites.google.com/view/jiesun/home). 
My research focused on applying concepts from machine learning, computer vision to develop algorithms to solve problems in fields related to biometrics and localization. My work has resulted in papers and presentations at conferences and symposiums (see resume for details).

If you are interested in knowing more about my research, please get in touch!

# Projects:

## 1. Designing a skin reflectance measure to mitigate bias across demographics in Face recognition

Face recognition (FR) systems are fast becoming ubiquitous. However, differential performance among certain demographics was identified in several widely used FR models. The skin tone of the subject is an important factor in addressing the differential performance. Previous work has used modeling methods to propose skin tone measures of subjects across different illuminations or utilized subjective labels of skin color and demographic information. However, such models heavily rely on consistent background and lighting for calibration, or utilize labeled datasets, which are time-consuming to generate or are unavailable. In this work, we have developed a novel and data-driven skin color measure capable of accurately representing subjects' skin tone from a single image, without requiring a consistent background or illumination. Our measure leverages the dichromatic reflection model in RGB space to decompose skin patches into diffuse and specular bases. 

## 2. Multi-user identification from keystroke data

Multi-user authentication from keystroke data is an open problem that needs to be solved. When an online account or a common desktop is shared among multiple users, there is a need to determine who the current user is at log-in. In this research, we propose a new technique to uniquely classify and identify multiple users accessing a single application using keystroke dynamics. This problem is usually encountered when multiple users have legitimate access to shared computers and accounts, where, at times, one user can inadvertently be logged in on another user's account. Since the login processes are usually bypassed at this stage, we rely on keystroke dynamics in order to tell users apart. Our algorithm uses the quantile transform and techniques from localization to classify and identify users. 
Specifically, we use an algorithm known as ordinal Unfolding based Localization (UNLOC), which uses only ordinal data obtained from comparing distance proxies, by ``locating'' users in a reduced PCA/Kernel-PCA/t-SNE space based on their typing patterns.  Our results are validated with the help of benchmark keystroke datasets and show that our algorithm outperforms other methods.  

