---
title: "Channel-wise reconstruction-based anomaly detection framework for multi-channel sensor data"
collection: publications
permalink: /publication/2020-01-01-channelwise-2
excerpt: 'Integration of convolutional autoencoder and anomaly detection model for vehicle condition monitoring.'
date: 2020-01-01
venue: 'Intelligent Systems and Applications: Proceedings of the 2019 Intelligent Systems Conference (IntelliSys)'
---

Anomaly detection is the task of learning patterns of normal data and identifying data with other characteristics. 
As various types of sensors are attached to vehicle, healthcare equipment, production facilities, etc., detecting anomalies in multi-channel sensor data has become very important. 
In sensor data, abnormal signals occur temporally during certain intervals of a few channels. 
It is very important to capture the characteristics of individual channel and cross-channel relationship in order to detect abnormal signals that occur locally for a short time interval. 
We propose a channel-wise reconstruction-based anomaly detection framework which consists of two parts: channel-wise reconstruction part with convolutional autoencoder (CAE) and anomaly scoring part with machine learning algorithms, isolation forest (iForest) and local outlier factor (LOF). 
CAE learns the features of normal signal data and measures channel-wise reconstruction error. 
We applied the symmetric skip-connections technique to build a CAE model for higher reconstruction performance. 
Given the channel-wise reconstruction error as an input, iForest and LOF summarize it to anomaly score. 
We present our results on data collected from real sensors attached to vehicle and show that the proposed framework outperforms traditional reconstruction-based anomaly detection methods and one-class classification methods.

[Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-29513-4_88)

Recommended citation: Kwak, M., & Kim, S. B. (2020). Channel-wise reconstruction-based anomaly detection framework for multi-channel sensor data. In <i>Intelligent Systems and Applications: Proceedings of the 2019 Intelligent Systems Conference (IntelliSys) Volume 2</i> (pp. 1222-1233). Springer International Publishing.