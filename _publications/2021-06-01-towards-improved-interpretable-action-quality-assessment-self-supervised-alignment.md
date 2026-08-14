---
title: "Towards Improved and Interpretable Action Quality Assessment with Self-Supervised Alignment"
collection: publications
category: conferences
permalink: /publication/2021-06-01-towards-improved-interpretable-action-quality-assessment-self-supervised-alignment
excerpt: ''
date: 2021-06-01
venue: 'HumanInteract Workshop, in conjunction with International Conference on Pervasive Technologies Related to Assistive Environments (PETRA 2021)'
paperurl: 'https://users.ics.forth.gr/~argyros/mypapers/2021_06_PETRA_AQA-Roditakis.pdf'
citation: 'Konstantinos Roditakis, Alexandros Makris and Antonis A. Argyros, "Towards Improved and Interpretable Action Quality Assessment with Self-Supervised Alignment", In HumanInteract Workshop, in conjunction with International Conference on Pervasive Technologies Related to Assistive Environments (PETRA 2021), ACM, Corfu, Greece, June 2021.'
---

**Abstract:**

Action Quality Assessment (AQA) is a video understanding task aiming at the quantification of the execution quality of an action. One of the main challenges in relevant, deep learning-based approaches is the collection of training data annotated by experts. Current methods perform fine-tuning on pre-trained backbone models and aim to improve performance by modelling the subjects and the scene. In this work we consider embeddings extracted using a self-supervised training method based on a differential cycle consistency loss between sequences of actions. These are shown to improve the state-of-the-art without the need for additional annotations or scene modelling. The same embeddings are also used to temporally align the sequences prior to quality assessment which further increases the accuracy, provides robustness to variance in execution speed and enables us to provide fine-grained interpretability of the assessment score. The experimental evaluation of the method on the MTL-AQA dataset, demonstrates significant accuracy gain compared to the state-of-the-art baselines which grows even more when the action execution sequences are not well aligned.