# Breast Cancer Image Classification

This repository contains code for a breast cancer image classification project. The goal of this project is to classify breast cancer images into three categories: benign, malignant, and normal. The project involves data preprocessing, feature extraction using Histogram of Oriented Gradients (HOG), and training machine learning models to achieve accurate classification.

## Table of Contents

- Installation
- Dataset
- Data Preparation
- Feature Extraction
- Model Training
- Evaluation
- Results
- Contributing
- License

## Installation

To run the code in this repository, you need to have Python installed along with the following libraries:

- numpy
- pandas
- seaborn
- os
- cv2 (OpenCV)
- matplotlib
- scikit-learn
- scikit-image

You can install the required libraries using the following command:

```bash
pip install numpy pandas seaborn opencv-python matplotlib scikit-learn scikit-image
```



## Dataset

The dataset used in this project consists of breast cancer images categorized into three classes: benign, malignant, and normal. Each category contains images and their corresponding masks.

## Data Preparation

The data preparation process involves the following steps:

1. **Importing Necessary Libraries**: Importing libraries for data manipulation, visualization, machine learning, and image processing.
2. **Preparing Image and Mask Paths**: Generating paths for images and masks, and storing them in a DataFrame.
3. **Balancing and Preparing the Final Dataset**: Sampling an equal number of benign and malignant cases, and combining them with normal cases. Mapping categorical labels to numerical values.

## Feature Extraction

The feature extraction process involves the following steps:

1. **Loading and Resizing Images and Masks**: Defining a function to load and resize images and masks.
2. **Extracting HOG Features**: Defining a function to extract Histogram of Oriented Gradients (HOG) features from images using masks.

## Model Training

The model training process involves the following steps:

1. **Extracting Features and Splitting the Dataset**: Extracting HOG features from images and splitting the dataset into training and testing sets.
2. **Training Machine Learning Models**: Defining functions to train Decision Tree, Random Forest, and Support Vector Machine (SVM) classifiers using Grid Search for hyperparameter tuning.

## Evaluation

The evaluation process involves the following steps:

1. **Evaluating the Model’s Performance**: Defining a function to evaluate the performance of machine learning models using classification reports and confusion matrices.

## Results

The results of the project include the best hyperparameters found by Grid Search, training and testing accuracies, and visualizations of confusion matrices for each model.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
