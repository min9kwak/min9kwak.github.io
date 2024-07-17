---
title: "Unsupervised abnormal sensor signal detection with channelwise reconstruction errors"
collection: publications
permalink: /publication/2021-03-09-unsupervised-3
excerpt: 'Channelwise reconstruction anomaly detection model for multichannel timeseries data, evaluated with simulations and automobile sensors.'
date: 2021-03-09
venue: 'IEEE Access'
---

Detecting an anomaly in multichannel signal data is a challenging task in various domains. 
It should take into account the cross-channel relationship and temporal relationship within each channel. 
Moreover, the signal data is high-dimensional and making it difficult to gather sufficient abnormal labels. 
Consequently, unsupervised reconstruction-based anomaly detection methods have been applied successfully in many studies. 
However, they lose valuable channel information inherent in the reconstruction errors by merely averaging the errors for both the channel and time, then consider the average value as an anomaly score. 
In this study, we propose a method to explicitly employ channelwise reconstruction errors as a feature to detect abnormal signals. 
After a convolutional autoencoder produces the channelwise reconstruction errors, a machine learning anomaly detection model aggregates the errors as an anomaly score. 
To demonstrate the effectiveness and applicability of the proposed model, we conduct experiments using simulated data and real-world automobile data. 
The results show that the proposed method remarkably enhances the detectability compared to the simple average of the reconstruction errors. 
The reconstruction errors of abnormal and normal channels are shown to be different; therefore, it can be considered as an appropriate feature for anomaly detection. 
The best performance is obtained by using local outlier factors in the following anomaly detection model.

[Paper Link](https://ieeexplore.ieee.org/abstract/document/9373362)

Recommended citation: Kwak, M., & Kim, S. B. (2021). Unsupervised abnormal sensor signal detection with channelwise reconstruction errors. <i>IEEE Access, 9</i>, 39995-40007.