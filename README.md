---
title: "Brain Tumor Classification Using Convolutional Neural Networks"
output: github_document
---

# Brain Tumor Classification Using Convolutional Neural Networks

## 🧠 Overview

This project implements an **Automatic Support Intelligent System** for the classification and detection of **brain tumors** from **MRI images** using:

- **Fast Discrete Curvelet Transformation (FDCT)** for texture extraction
- **Gray-Level Co-occurrence Matrix (GLCM)** for feature extraction
- **Probabilistic Neural Network (PNN)** with **Radial Basis Function (RBF)** for classification
- **Fuzzy Clustering** for tumor segmentation

The system classifies brain tumors into **Benign**, **Malignant**, or **Normal** and enhances early detection, improving the chances of timely treatment.

---

## 🎯 Objectives

- Automate the classification of brain tumors using image processing and AI.
- Apply efficient texture and statistical feature extraction methods.
- Use PNN for accurate and fast tumor classification.
- Segment brain structures using fuzzy logic for structural analysis.

---

## 🔧 Methodology

### 1. Image Preprocessing
- MRI images are preprocessed using MATLAB.
- Converted into grayscale matrices for analysis.

### 2. Feature Extraction
- **FDCT** is used to capture high-frequency textures.
- **GLCM** extracts Haralick features such as energy, contrast, correlation, and homogeneity.

### 3. Classification
- A **PNN-RBF network** is trained on the extracted features.
- The output layer provides probabilities for tumor type.

### 4. Segmentation
- **Fuzzy C-Means Clustering** segments tumor regions.
- Morphological operations refine the segmented area.

---

## 📁 Project Structure

