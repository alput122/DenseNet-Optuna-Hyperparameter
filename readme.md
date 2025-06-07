# DenseNet-Optuna-Hyperparameter 🧠

![DenseNet](https://img.shields.io/badge/DenseNet-Optuna_Hyperparameter-brightgreen.svg)  
[![Releases](https://img.shields.io/badge/Releases-latest-blue.svg)](https://github.com/alput122/DenseNet-Optuna-Hyperparameter/releases)

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Web Application](#web-application)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

Welcome to the **DenseNet-Optuna-Hyperparameter** repository. This project aims to provide a robust deep learning solution for classifying Alzheimer's disease stages using advanced DenseNet architectures. We leverage Optuna for hyperparameter tuning to enhance model performance. 

For the latest updates and releases, please visit our [Releases page](https://github.com/alput122/DenseNet-Optuna-Hyperparameter/releases).

## Project Overview

Alzheimer's disease is a complex condition that affects millions worldwide. Early detection can significantly impact treatment outcomes. This project implements multiple DenseNet variants, such as DenseNet121, DenseNet169, and DenseNet201, to classify Alzheimer's disease stages based on brain MRI images. 

By utilizing Optuna, we optimize hyperparameters effectively, allowing for better model performance and accuracy. This repository serves as a comprehensive resource for researchers and developers interested in medical AI and neuroimaging.

## Features

- **Multiple DenseNet Variants**: Implementations of DenseNet121, DenseNet169, and DenseNet201.
- **Optuna Hyperparameter Tuning**: Efficiently optimize model parameters to improve performance.
- **Transfer Learning**: Utilize pre-trained models to enhance learning efficiency.
- **Web Application**: A user-friendly interface for model interaction and results visualization.
- **Evaluation Metrics**: Comprehensive metrics to assess model performance.

## Technologies Used

- **Deep Learning Framework**: Keras, TensorFlow
- **Hyperparameter Tuning**: Optuna
- **Web Application**: Streamlit
- **Image Processing**: OpenCV, NumPy
- **Data Handling**: Pandas, Matplotlib

## Dataset

The dataset used in this project is sourced from the **Alzheimer's Disease Neuroimaging Initiative (ADNI)**. It includes a diverse set of brain MRI images categorized by Alzheimer's disease stages. Proper data preprocessing is crucial for effective model training.

### Data Preprocessing Steps

1. **Image Resizing**: Standardize image sizes for input into the model.
2. **Normalization**: Scale pixel values to a range suitable for neural networks.
3. **Augmentation**: Apply transformations to increase dataset diversity.

## Installation

To set up the project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/alput122/DenseNet-Optuna-Hyperparameter.git
   cd DenseNet-Optuna-Hyperparameter
   ```

2. **Install Required Packages**:
   Use pip to install the necessary packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the Dataset**:
   Follow the instructions in the `data/README.md` file to download and organize the dataset.

## Usage

Once the installation is complete, you can start using the project.

### Running the Model

To train the model, execute the following command:
```bash
python train.py
```

### Running the Web Application

To launch the web application, use:
```bash
streamlit run app.py
```

## Training

Training the model involves specifying hyperparameters. Optuna will assist in tuning these parameters to find the best configuration.

### Training Parameters

- **Batch Size**: Number of samples processed before the model is updated.
- **Learning Rate**: The step size at each iteration while moving toward a minimum of the loss function.
- **Epochs**: Number of complete passes through the training dataset.

## Evaluation

After training, evaluate the model using the test dataset. Metrics such as accuracy, precision, recall, and F1-score will provide insights into model performance.

### Evaluation Metrics

- **Accuracy**: Proportion of true results among the total number of cases examined.
- **Precision**: Ratio of correctly predicted positive observations to the total predicted positives.
- **Recall**: Ratio of correctly predicted positive observations to all actual positives.
- **F1-Score**: Weighted average of precision and recall.

## Results

The results of the model training and evaluation will be stored in the `results/` directory. You can visualize the performance metrics and compare different DenseNet variants.

## Web Application

The web application allows users to interact with the model easily. Users can upload brain MRI images and receive classification results.

### Features of the Web App

- **Image Upload**: Users can upload their own MRI images.
- **Classification Output**: Displays the predicted stage of Alzheimer's disease.
- **Visualization**: Provides visual feedback on model predictions.

## Contributing

We welcome contributions to enhance this project. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature.
3. Make your changes and commit them.
4. Push to your branch and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

- **ADNI**: For providing the dataset used in this project.
- **Keras**: For the deep learning framework.
- **Optuna**: For hyperparameter optimization.
- **Streamlit**: For the web application framework.

For the latest updates and releases, please visit our [Releases page](https://github.com/alput122/DenseNet-Optuna-Hyperparameter/releases).