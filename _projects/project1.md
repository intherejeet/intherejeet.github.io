
---
title: "Anomaly Detection using Capsule Networks for High-dimensional Datasets"
collection: publications
permalink: /publication/2019-03-31-capsulenet-anomaly
excerpt: 'This paper presents the use of capsule networks for anomaly detection.'
date: 2019-03-31
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2112.13514.pdf'

---
Anomaly detection is an essential problem in machine learning. Application areas include network security, health care, fraud detection, etc., involving high-dimensional datasets. A typical anomaly detection system always faces the class-imbalance problem in the form of a vast difference in the sample sizes of different classes. They usually have class overlap problems. This study used a capsule network for the anomaly detection task. To the best of our knowledge, this is the first instance where a capsule network is analyzed for the anomaly detection task in a high-dimensional complex data setting. We also handle the related novelty and outlier detection problems. The architecture of the capsule network was suitably modified for a binary classification task. Capsule networks offer a good option for detecting anomalies due to the effect of viewpoint invariance captured in its predictions and viewpoint equivariance captured in internal capsule architecture. We used six-layered under-complete autoencoder architecture with second and third layers containing capsules. The capsules were trained using the dynamic routing algorithm. We created 10-imbalanced datasets from the original MNIST dataset and compared the performance of the capsule network with 5 baseline models. Our leading test set measures are F1-score for minority class and area under the ROC curve. We found that the capsule network outperformed every other baseline model on the anomaly detection task by using only ten epochs for training and without using any other data level and algorithm level approach. Thus, we conclude that capsule networks are excellent in modeling complex high-dimensional imbalanced datasets for the anomaly detection task.

[Download paper here]('https://arxiv.org/pdf/2112.13514.pdf')
