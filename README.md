# CNN Binary Classification: Muffins and Chihuahuas

Welcome to our project on CNN Binary Classification for distinguishing between muffins and chihuahuas. This repository contains the code and documentation for our Master’s Degree project in Computer Science at the Università degli Studi di Milano, A.A. 2023-2024.

## Overview

This project aims to solve the challenging and amusing task of teaching a computer to differentiate between images of muffins and chihuahuas. This task is approached using various neural network architectures, with a focus on Convolutional Neural Networks (CNNs) and EfficientNet, leveraging libraries such as Keras and TensorFlow.

## Contents

- **Introduction**
  - Overview of the project, tools, and libraries used.
- **Data Preprocessing**
  - Steps taken to preprocess the dataset including hashing, resizing, and manual inspection.
  - Data augmentation techniques applied to improve model performance.
- **Architectures of Neural Networks**
  - Detailed descriptions of the different neural network architectures explored, including Multi-Layer Perceptron (MLP), Basic CNN, Random Search CNN, and EfficientNet.
- **Hyperparameter Tuning**
  - Explanation of the hyperparameter tuning methods used: Random Search and Bayesian Optimization.
- **Training of Neural Networks**
  - Description of the training process, techniques employed, and outcomes.
- **Results**
  - Validation results, risk estimates, evaluation metrics, and graphical representations of the confusion matrices.

## Files

- `Report.pdf`: The detailed project report.
- `dataset/`: Directory containing the dataset images.
- `SMfML_Rinaldi_Cannone.ipynb`: Jupyter notebook used for experimentation and analysis.

## Requirements

- Python 3.8+
- TensorFlow 2.4+
- Keras 2.4+
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Usage

1. **Data Preprocessing and Training**:
   - Open and run the `SMfML_Rinaldi_Cannone.ipynb` notebook to preprocess the dataset, train the models, and evaluate their performance.

## Project Structure

```
muffins-vs-chihuahuas/
│
├── dataset/
│   ├── test/
│   └── train/
│
├── SMfML_Rinaldi_Cannone.ipynb
├── Report.pdf
└── README.md
```

## Results

The results of our experiments show that EfficientNet, combined with Bayesian Optimization for hyperparameter tuning, achieved the highest accuracy and robustness among all tested models. The detailed results and risk estimates can be found in the `Results` section of the project report.
