
# Melanoma Detection

Melanoma Detection is a machine learning project aimed at classifying melanoma from images using Convolutional Neural Networks (CNNs). This project involves data preparation, augmentation, model training, and evaluation to create a robust system for early melanoma detection. The project was developed in collaboration with a fellow student as part of a data science workshop.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Melanoma Detection is designed to aid in the early detection of melanoma by classifying skin lesion images. The system uses deep learning techniques, specifically Convolutional Neural Networks (CNNs), to analyze and classify images. This project was completed in collaboration with a fellow student as part of a data science workshop.

## Features

- **Data Preparation**: Load and preprocess skin lesion images.
- **Data Augmentation**: Apply various augmentation techniques to enhance model robustness.
- **Model Training**: Train a CNN model using FastAI's ResNet18 architecture.
- **Model Evaluation**: Assess model performance using various metrics.

## Installation

To run the Melanoma Detection project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Shay-Gabison/Melanoma-Detection.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Melanoma-Detection
   ```

3. Install the required dependencies. You can use `pip` to install the necessary Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To train the model and evaluate its performance, follow these steps:

1. Ensure that you have your dataset organized in the appropriate directories (training, validation, and testing).

2. Run the main training script:
   ```bash
   python train_model.py
   ```

3. After training, evaluate the model:
   ```bash
   python evaluate_model.py
   ```

## Data

The dataset used for this project consists of skin lesion images, organized into training, validation, and test sets. The data is preprocessed and augmented to balance the classes and enhance model performance.

- **Data Source**: [Link to dataset or dataset description]
- **Data Structure**: The dataset should be organized as follows:
  ```
  data/
  ├── train/
  │   ├── melanoma/
  │   └── non_melanoma/
  ├── valid/
  │   ├── melanoma/
  │   └── non_melanoma/
  └── test/
      ├── melanoma/
      └── non_melanoma/
  ```

## Model Architecture

The project uses a Convolutional Neural Network (CNN) with the following architecture:

- **Base Model**: ResNet18
- **Framework**: FastAI
- **Data Augmentation**: Techniques including rotation, scaling, and color jittering

## Results

The model achieved an error rate of 0.17 after training for 4 epochs, which corresponds to a precision of 83%. Future improvements may include further data augmentation, hyperparameter tuning, and experimentation with different CNN architectures.

## Contributing

This project was developed in collaboration with a fellow student. Contributions are welcome. To contribute:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to the branch.
5. Create a pull request.

