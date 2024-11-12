---
title: "Enhancing Speech Emotion Recognition through Multi-Dataset Analysis and Deep Learning"
authors:
- Sagar Swami Rao Kulkarni (saku8738)
- Idriss Djiofack Teledjieu (iddj6806)
date: "2024-06-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "CSCI 5922 - Deep Learning"
publication_short: "CSCI 5922"

abstract: |
    Speech Emotion Recognition (SER) has gained significant attention in recent years due to its potential applications in human-computer interaction, mental health monitoring, and customer service. Accurately identifying emotional states from speech can lead to more empathetic and personalized interactions between humans and machines, ultimately improving user experience and satisfaction. Moreover, SER can aid in early detection of mental health issues and contribute to the development of effective intervention strategies.

    Despite the progress made in SER, existing solutions often face limitations such as lack of generalization across different datasets, languages, and recording conditions. Many studies focus on a single dataset, which may not capture the full range of emotional expressions and acoustic variability present in real-world scenarios. Furthermore, the performance of SER systems can be hindered by the limited size and diversity of the training data, as well as the inherent subjectivity in emotion annotation.

    To address these limitations, we propose a novel approach that leverages the combination of two widely used datasets, RAVDESS and CREMA-D, to enhance the robustness and generalization capabilities of SER systems. By merging these datasets, we aim to capture a broader range of emotional expressions and acoustic characteristics, enabling the development of a more comprehensive and reliable SER model. We will explore various feature extraction methods and develop a deep learning model that can effectively learn from the merged dataset. Our proposed solution is expected to outperform single-dataset approaches and exhibit improved cross-dataset generalization.

# Summary. An optional shortened abstract.
summary: |
    This paper proposes a multi-dataset approach to enhance Speech Emotion Recognition (SER) using deep learning. By merging the RAVDESS and CREMA-D datasets, we capture a broader range of emotional expressions and acoustic characteristics, aiming to improve model robustness and cross-dataset generalization.

tags:
- Speech Emotion Recognition
- Deep Learning
- Multi-Dataset Analysis

featured: true

links:
- name: Project Code
  url: 'https://github.com/user/project'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""
---

## 1. Introduction
Speech Emotion Recognition (SER) has gained significant attention in recent years due to its potential applications in human-computer interaction, mental health monitoring, and customer service. Accurately identifying emotional states from speech can lead to more empathetic and personalized interactions between humans and machines, ultimately improving user experience and satisfaction. Moreover, SER can aid in early detection of mental health issues and contribute to the development of effective intervention strategies.

To address these limitations, we propose a novel approach that leverages the combination of two widely used datasets, RAVDESS and CREMA-D, to enhance the robustness and generalization capabilities of SER systems.

## 2. Related Work

### 2.1 Speech Emotion Recognition
Studies by Zengzhao et al., K Bhangale et al., and Jiaxin Ye et al. have advanced SER through various methodologies, though single-dataset limitations remain.

### 2.2 Deep Learning for SER
Research by Pan et al., Jagadeeshwar et al., and Liu et al. explores deep learning architectures, which we build upon with a multi-dataset approach.

### 2.3 Cross-Dataset SER
Our work differentiates by directly merging datasets to increase diversity in the training set, inspired by works like those of Nasersharif et al. and Zhao et al.

### 2.4 Feature Extraction for SER
Building on feature extraction methods from Chen et al. and Zvarevashe et al., we explore combinations to enhance our model's performance.

## 3. Methods

### 3.1 Data Preparation
- Load individual datasets (RAVDESS and CREMA-D)
- Merge datasets, visualize distributions
- Apply augmentation to balance classes and increase dataset size

### 3.2 Feature Extraction
- Extract features like zero-crossing rate, RMS energy, MFCCs
- Experiment with different feature sets and combinations

### 3.3 Model Development
- Train deep learning models (CNN, LSTM, Transformer, GRU) on both individual and combined datasets

### 3.4 Model Evaluation
- Use accuracy, precision, recall, and F1-score metrics
- Cross-dataset evaluations to assess generalization

## 4. Experiments

### 4.1 Individual and Combined Dataset Models
Purpose: Evaluate SER models on individual and combined datasets.

### 4.2 Comparative Analysis: Impact of Merging the Datasets
Purpose: Compare performance and analyze generalization improvements from merged datasets.

## References
1. Chen, L., et al. (2022). Learning-based Speech Emotion Recognition. *Expert Systems with Applications*, 207.
2. Bhangale, K.B., et al. (2023). Deep Learning-Based SER: A Review. *Electronics*, 12(4), 839.
3. Ye, Z., et al. (2023). Temporal Convolutional Networks for SER. *IEEE Signal Processing Letters*, 30.
4. Pan, S-T., et al. (2023). Combining 1D CNN and LSTM for SER. *Electronics*, 12(11), 2436.
5. Jagadeeshwar, K., et al. (2023). ASERNet: MFCC-based CNN for SER. *Int. J. Model. Simul. Sci. Comput.*, 14(04), 2341029.
6. Liu, Y., et al. (2024). Feature-level fusion in SER. *Multimedia Tools Appl.*, 1-21.
7. Nasersharif, B., et al. (2023). Multi-layer MMD in Cross-Corpus SER. *J. Supercomput.*, 79(12), 13031-13049.
