# Stroke Identification: A Machine Learning-Based Diagnostic Model Using Neuroimages

This repository contains the code implementation for the paper titled "Innovations in Stroke Identification: A Machine Learning-Based Diagnostic Model Using Neuroimages". The model uses machine learning techniques to identify strokes from neuroimages.

## Table of Contents
- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)
- [References](#references)
  
## Introduction
In this paper, we propose a machine learning-based diagnostic model for stroke identification using neuroimages. The model initially leveraged Convolutional Neural Networks (CNNs) and Bidirectional Long Short-Term Memory (BiLSTM) networks. We have since incorporated Principal Component Analysis (PCA) as a technique to improve accuracy and performance.

## Dependencies
To run the code in this repository, you will need the following dependencies:
- Python 3.x
- TensorFlow
- NumPy
- scikit-learn

## Dataset
The model is trained and tested using the following dataset:
- [Brain CT Images with Intracranial Hemorrhage Masks](https://www.kaggle.com/datasets/vbookshelf/computed-tomography-ct-images)

## Results
The improved model, which uses PCA instead of the genetic algorithm (GA) previously mentioned, achieved an accuracy of 97.60%. This enhancement shows the effectiveness of PCA in optimizing the feature selection process, leading to significantly better performance compared to the initial accuracy of 61.27% uisng GA algorithm and it out perform paper result 96.60 % accuracy.

## Contributing
Contributions are welcome! If you would like to contribute to this project, please feel free to open an issue or submit a pull request.

## References
- [Innovations in Stroke Identification: A Machine Learning-Based Diagnostic Model Using Neuroimages](https://ieeexplore.ieee.org/document/10445193)
