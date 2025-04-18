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

# Brain Image Segmentation using OpenCV

This project demonstrates the process of preprocessing and segmenting a brain scan image using classic image processing techniques in Python with OpenCV.

## 📌 Project Overview

The notebook performs the following steps:
- Loads and displays a brain scan image
- Converts it to grayscale
- Applies median filtering to remove salt-and-pepper noise
- Detects edges using Sobel operators
- Applies thresholding for binarization
- Performs morphological operations to clean up the image
- Uses distance transform and thresholding for foreground extraction

## 🧰 Libraries Used

Make sure the following libraries are installed:

```bash
pip install opencv-python matplotlib numpy


## 📁 Project Structure

Monish.ipynb: Main Jupyter notebook with the step-by-step implementation.

brain.png: The brain scan image used (ensure it's in the same directory as the notebook).

🚀 How to Run
Clone the repository or download the files.

Ensure brain.png is in the same folder as the notebook.

Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Monish.ipynb
Run the cells in order to see the image processing pipeline in action.

📈 Output
The output includes visualizations of:

Original and grayscale images

Filtered image

Edge detection results

Binary mask after thresholding

Final segmented regions

