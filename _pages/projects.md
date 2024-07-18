---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## Research Projects (Georgia Institute of Technology)
1. <span style="color:blue;">[NIH]</span> Image-based Models of Tumor-Immune Dynamics in Glioblastoma
   - 2023.10 ~ Present
   - Developed conditional diffusion & transformer models for translating tumorous brain images into healthy brain images for reducing patient heterogeneity.
   - Trained the model on benchmark datasets and applied it to internal datasets.
   - Utilized generated normal and original images to construct an epidermal growth factor receptor (EGFR) classification model.
   - Developed a brain image preprocessing tool that transforms MRIs, region of interests (ROIs), and biopsy locations into BraTS atlas [(Repo)](https://github.com/min9kwak/preprocessing).

2. <span style="color:blue;">[NIH]</span> AIDen: An AI-Empowered Detection and Diagnosis System for Jaw Lesions Using CBCT
   - 2022.08 ~ Present
   - Integrated domain knowledge into a deep semantic segmentation model for precise lesion detection in 3D CBCT images.
   - Applied knowledge of lesion occurrence near tooth roots to regularize and guide the segmentation model.
   - Significantly improved the detection and segmentation performance of small lesions.

3. <span style="color:blue;">[NIH]</span> Multi-Modality Image Data Fusion and Machine Learning Approaches for Personalized Diagnostics and Prognostics of MCI due to AD
   - 2022.04 ~ Present
   - Developed a self-supervised contrastive model for classifying MCI converters and non-converters using 3D amyloid-PET images, incorporating label information during the pre-training step.
   - Created a mutual knowledge distillation model for handling incomplete multi-modal 3D image data (MRI and amyloid-PET) in MCI conversion classification.
   - Designed a novel teacher model that enhances knowledge distillation by focusing on modality-common representation.

## Research Projects (Korea University)
1. <span style="color:blue;">[Samsung Advanced Institute of Technology]</span> Developing Non-Invasive Lipid Measurement Algorithm Based on 2D Array Sensor
   - 2020.05 ~ 2021.04
   - Developed a method to predict blood lipid concentrations using optical sensor data, eliminating the need for blood draws.
   - Designed a data preprocessing framework to predict lipid levels from sensor data.
   - Implemented a hybrid approach combining autoencoders and machine learning algorithms.

2. <span style="color:blue;">[Samsung Electronics]</span> Congestion-Aware Control of Overhead Hoist Vehicles in Semiconductor Fabrication Logistics
   - 2020.05 ~ 2020.12
   - Developed an adaptive agent to control transportation vehicles in semiconductor FABs, aiming to minimize traffic congestion.
   - Applied imitation learning and data augmentation techniques within a deep reinforcement learning framework.

3. <span style="color:blue;">[Korea Institute of Startup and Entrepreneurship Development]</span> Text Mining and Trend Analysis on Venture Companies and Startups
   - 2020.03 ~ 2020.07
   - Conducted web crawling to collect news articles on venture companies and startups and performed text mining analysis to identify key trends and keywords by year.
   - Used community detection algorithms to group keywords and built a pipeline for hierarchical trend analysis.
   - Performed sentiment analysis to evaluate positive and negative impacts of government policies, and included findings in government agency reports.

4. <span style="color:blue;">[Hanwha ICT]</span> Conversational Platform R\&D: Machine Reading Comprehension with Large Language Models
   - 2019.05 ~ 2019.12
   - Developed text question answering methods for both Korean news articles and in-house regulation documents to ensure compliance.
   - Trained large language models (e.g., BERT) and distilled them into smaller models for deployment (e.g., DistilBERT).

5. <span style="color:blue;">[Hyundai Motors and DS-eTrade]</span> Durability Monitoring System for Road Simulator
   - 2019.04 ~ 2019.12
   - Developed an algorithm to detect abnormal states and problematic parts of vehicles during road simulator operations.
   - Implemented a hierarchical feedforward attention network to detect abnormal states and explain the causes.

6. <span style="color:blue;">[Hyundai Motors and DS-eTrade]</span> Detecting and Categorizing Failure Patterns of EGR Valve
   - 2019.04 ~ 2019.12
   - Predicted failures in EGR valves of diesel cars and analyzed sensors causing these failures.
   - Implemented a hierarchical feedforward attention network to detect failures and identify critical sensors and time steps.
   - Utilized sensor-level attention scores to cluster failure patterns.

7. <span style="color:blue;">[Samsung Electronics]</span> Classification of Signal Patterns for Abnormal Cause Analysis of Semiconductor Logistics Systems
   - 2019.03 ~ 2019.11
   - Developed a framework consisting of anomaly detection, anomaly pattern clustering, and classification of logistics indices.
   - Discovered meaningful anomaly patterns by clustering channelwise reconstruction errors.
   - Employed an open-set model capable of classifying known classes and detecting unseen classes not present in training data.

8. <span style="color:blue;">[Hyundai Heavy Industries and Youngshine D&C]</span> AI-Based Smart Construction to Reduce Costs by 20%
   - 2016.09 ~ 2020.12
   - Conducted a study to predict construction equipment failures by analyzing sensor data.
   - Employed incremental PCA to adapt to changing data distributions over time, creating a lightweight model that can be easily embedded in equipment control systems.

9. <span style="color:blue;">[Samsung Electronics]</span> Deep Learning-Based Reliability Diagnosis Process Improvement
   - 2018.05 ~ 2019.04
   - Conducted a study on machine learning methods for early diagnosis and prediction of wafer quality in sub-10nm logic technology.
   - Applied domain knowledge-based and machine learning-based methods for missing data imputation.

10. <span style="color:blue;">[Electronics and Telecommunications Research Institute]</span> ICT-Based Crime Risk Prediction and Response Platform Development for Early Awareness of Risk Situations
    - 2018.04 ~ 2018.12
    - Developed a method combining criminal data with various public data to predict near-future crime reports.
    - Considered a combination of recurrent neural networks and ensemble algorithms as the prediction model.
    - Developed a software tool for visualizing crime report statuses.

11. <span style="color:blue;">[Hyosung Heavy Industries]</span> Advancing Health Index Module for 154kV Substation Facilities
    - 2018.09 ~ 2018.12
    - Conducted a study to improve the accuracy of a pre-developed health index module.
    - Applied the advanced module to various types of facilities to demonstrate its generality.

12. <span style="color:blue;">[Hyosung Heavy Industries]</span> Optimal Decision-Making System for Maintenance and Health Index Module for 154kV Substation Facilities
    - 2017.12 ~ 2018.03
    - Developed a system for optimal maintenance decisions for multiple facilities within a limited budget.
    - Applied dynamic programming and integer programming to optimize the decision-making process.
    - Designed a decision-making pipeline with gradient boosting machines to predict health indices and calculate feature importance for inspection items.
    - Implemented the pipeline into a monitoring system for real customers.

13. <span style="color:blue;">[Hyundai Heavy Industries]</span> Forecasting Demand for Construction Equipment Parts Using Big Data Analysis
    - 2016.10 ~ 2017.07
    - Predicted monthly demand for construction equipment parts and designed an objective dealer evaluation indicator by comparing predicted values to actual sales.
    - Developed software for visual comparisons of actual sales, predicted demands, and evaluation indicators by region, dealer, and part.
