
# Chest CT-Scan Image Classification

## Overview
This repository contains a machine learning project focused on the classification of chest CT-scan images. The project's goal is to distinguish between various types of lung carcinomas and healthy tissue. The dataset used for this project was obtained from Kaggle: [Chest CT-Scan Images](https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images/data).

## Dataset
The dataset includes CT-scan images categorized into different folders representing various conditions, including different types of lung cancer and normal scans. Due to the sensitive nature of medical datasets, appropriate measures were considered to handle the data responsibly.

## Methodology
A Convolutional Neural Network (CNN) was employed for this multi-class classification task. The process involved:
- Data preprocessing and augmentation to introduce variability into the dataset, thereby helping the model generalize better.
- The implementation of L2 regularization to prevent overfitting, with lambda tuning to find the optimal regularization strength.
- Learning rate adjustments for the optimization process.
- A custom CNN architecture with three convolutional layers was constructed to learn features from the images.

## Results
The initial model showed signs of underfitting, with modest performance on the training data and poor generalization to validation and test sets. Measures such as increasing model complexity and addressing class imbalance are considered for future improvements.

## Future Work
Improvements planned for subsequent iterations of the project include:
- Enhancing the model's architecture to increase complexity and capacity for learning nuanced features.
- Implementing techniques to address class imbalance in the dataset, potentially through data augmentation or class reweighting.
- Further hyperparameter tuning to optimize the learning rate, regularization strength, and other model parameters.

## Usage
The code is structured to allow easy replication of the results and further experimentation. Model weights are saved and can be loaded for additional evaluation or inference.

## Acknowledgements
The dataset used in this project is courtesy of the [Kaggle dataset](https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images/data) provided by Mohamed Hany. The work completed in this project is a testament to the potentials of machine learning in medical imaging.

## Contact
For any queries regarding this project, please feel free to contact [Your Name].
