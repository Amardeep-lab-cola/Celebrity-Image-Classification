# Sports Celebrity Image Classification

This repository contains a project aimed at classifying images of sports celebrities using machine learning techniques. The project involves data preprocessing, model training, and evaluation to achieve accurate identification of sports celebrities.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Sports celebrity image classification is a task in computer vision where the goal is to predict which sports celebrity is present in a given image. This project uses various deep learning techniques to build and evaluate models for this purpose.

## Dataset

The dataset used in this project consists of images of various sports celebrities. The images are labeled with the names of the celebrities they depict. 

## Data Preprocessing

Data preprocessing is a critical step to ensure the quality of the data and improve the performance of the model. The following steps were taken:
- Resizing images to a uniform size.
- Normalizing pixel values.
- Splitting the dataset into training, validation, and test sets.
- Data augmentation to increase the diversity of the training data.

## Model Training
- SVM(Support Vector Machine)
- Logistic Regression
- Random Forest

## Evaluation

The performance of the models was evaluated using metrics such as accuracy, precision, recall, and F1-score. Cross-validation was used to assess the model's ability to generalize to unseen data.

## Results

The best-performing model was found to be SVM, which achieved an accuracy of 84% on the test set. The detailed results and performance metrics are as follows:
- Accuracy: 90%


## Conclusion

This project demonstrates the application of deep learning techniques in sports celebrity image classification. The results indicate that SVM is effective in accurately identifying sports celebrities in images.

