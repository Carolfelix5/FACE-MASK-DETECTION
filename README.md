# Face Mask Detection

This project aims to classify images into two categories: "with mask" and "without mask" using deep learning. The model is trained using CNN and evaluated with various performance metrics.

## Features
- Image preprocessing and augmentation.
- Deep learning model for classification.
- Evaluation with confusion matrices and accuracy metrics.
- Data visualization using Matplotlib and Seaborn.

## Installation
To run this project, install the required dependencies:

```bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn scikit-image
```

## Dataset
Ensure the dataset is available in the expected format before running the notebook. The dataset should contain images categorized into "Mask" and "No Mask".

## Model
The model is built using CNN and consists of multiple layers, including:

* Convolutional layers for feature extraction.
* Pooling layers for dimensionality reduction.
* Fully connected layers for classification.

## Results
* The trained model achieves high accuracy in detecting face masks.
* Performance is evaluated using confusion matrices and accuracy scores.
