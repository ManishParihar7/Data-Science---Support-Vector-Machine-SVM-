# Data-Science---Support-Vector-Machine-SVM-
# Salary and Forest Fire Size Category Classification using SVM

## Problem Statement

This project involves building classification models using Support Vector Machines (SVM) for two distinct datasets: salary data and forest fire size category data. The primary objectives include:

1. Predicting salary categories (above or below $50,000) based on various features in the salary dataset.
2. Classifying forest fire size categories (small or large) using environmental factors in the forest fire dataset.

## Table of Contents

- [Introduction](#introduction)
- [Datasets](#datasets)
- [Prerequisites](#prerequisites)
- [Problem Statement 1: Salary Data Classification](#problem-statement-1-salary-data-classification)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Data Preprocessing](#data-preprocessing)
  - [SVM Models](#svm-models)
- [Problem Statement 2: Forest Fire Size Category Classification](#problem-statement-2-forest-fire-size-category-classification)
  - [Data Preprocessing](#data-preprocessing-1)
  - [SVM Models](#svm-models-1)
- [Conclusion](#conclusion)
- [Getting Started](#getting-started)
- [Author](#author)
- [License](#license)

## Introduction

This project focuses on the application of Support Vector Machines (SVM) for classification tasks. Two distinct datasets are used to predict salary categories and classify forest fire size categories. The models' performance is evaluated based on accuracy and confusion matrices.

## Datasets

The project uses two datasets:

1. **Salary Data**: Contains information about individuals, including features like education, occupation, and workclass, to predict salary categories above or below $50,000.

2. **Forest Fire Size Category Data**: Includes environmental factors like FFMC, DMC, temperature, humidity, etc., to classify forest fire size categories as small or large.

## Prerequisites

Make sure to install the following libraries before running the code:

- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-Learn

You can install these libraries using `pip install`.

## Problem Statement 1: Salary Data Classification

### Exploratory Data Analysis

The code begins by exploring the salary dataset, checking for missing values, and performing data analysis on the training and testing datasets.

### Data Preprocessing

Categorical columns are encoded using LabelEncoder, and the data is normalized to ensure uniform scales.

### SVM Models

Several SVM models are created using different kernels (linear, polynomial, radial basis function, and sigmoid). The accuracy and confusion matrices are evaluated for each model.

## Problem Statement 2: Forest Fire Size Category Classification

### Data Preprocessing

The forest fire dataset is preprocessed by normalizing the data to handle scale differences.

### SVM Models

SVM models are built for forest fire size category classification using different kernels (linear, polynomial, radial basis function, and sigmoid). Accuracy is calculated for each model.

## Conclusion

The README file provides an overview of the SVM classification models, including their accuracy and key findings. You can find detailed code and results in the Jupyter Notebook files provided in this repository.

## Getting Started

You can run the classification models for salary data and forest fire size categories by following the code in the Jupyter Notebook files provided.

## Author

[Manish Parihar]

## License

This project is licensed under the MIT License.
