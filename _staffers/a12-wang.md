---
name: Jun-Kun Wang
email: jkw005@ucsd.edu
photo: assets/images/jun-kun.png
website: https://jimwang123.github.io/
domain: A12
title: Tackling Distribution Shifts via Test-Time Adaptation and Optimization
bio: "I am an assistant professor at HDSI and ECE. My research is centered around optimization and its connections with statistics and machine learning. "
description: "Tackling the problems of machine learning under distribution shifts has drawn great interest due to the emerging concern regarding the reliability of machine learning techniques when applied to real-world systems, where distribution shifts between training and testing data are often unavoidable. For example, in medical applications, machine learning model were typically trained on data that were collected from some specific institutions, while the model is adopted by institutions outside the training set, and hence distribution shifts naturally occur. The challenges of distribution shifts also arise in many other fields, e.g., robotics, ML for education, ML for agriculture, or ML for wildlife monitoring, to name just a few.<br><br>

Test-time adaptation is a task for tackling distribution shifts. It refers to adapting a model from a source-domain to a new domain at test time, where only unlabeled samples from the new domain are accessible. Its applications include predictions on sensor data, climate data, medical images, in which distribution shifts of data could occur at test time and annotating the labels could be costly. A common approach in test-time adaptation is constructing pseudo-labels for those unlabeled samples and using optimization methods like gradient descent to minimize a certain loss function with the pseudo-labels to update the model. In this capstone project, we will leverage optimization techniques to speed up adaptation to the new domain. Students will have substantial hands-on (PyTorch) experiences, from reproducing existing algorithms to designing and implementing their own methods."
summer: "Complete reading the following three relevant papers:<br>

Continual Test-Time Domain Adaptation
Qin Wang, Olga Fink, Luc Van Gool, Dengxin Dai
https://arxiv.org/abs/2203.13591
CVPR 2022<br><br>

On Pitfalls of Test-Time Adaptation
Hao Zhao, Yuejiang Liu, Alexandre Alahi, Tao Lin
ICML 2023
https://proceedings.mlr.press/v202/zhao23d/zhao23d.pdf<br><br>

Test Time Adaptation via Conjugate Pseudo-labels
Sachin Goyal, Mingjie Sun, Aditi Raghunathan, J. Zico Kolter
https://arxiv.org/abs/2207.09640
NeurIPS 2022"
oldstudent: nan
prerequisites: Optimization will be fundamental to this capstone project. It is *highly recommended* to take an undergraduate-level optimization course in the Fall quarter, e.g., ECE 174 Intro/Linear&Nonlinear Optimization or  MATH 173A Optimization/Data Science I
time: Friday 1-2PM, In-Person
style: Students will be expected to use Python/PyTorch to implement their algorithms (and should be able to code).
seats: 4
tag: Theoretical Foundations
---