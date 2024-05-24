# SecureSign - Signature Detection using Machine Learning Methods

SecureSign is a robust signature detection and verification system developed using advanced machine learning techniques. This project aims to accurately distinguish between genuine signatures and skilled forgeries, particularly in offline signature verification scenarios.

## Introduction

Signature plays a crucial role in our lives, whether handwritten or digital. The detection of falsified signatures is a critical aspect of biometric authentication. Traditional methods relied on forensic analysts, but advancements in AI and ML have significantly improved this field.

## Problem Definition

The project addresses the challenge of accurately distinguishing between genuine signatures and well-executed forgeries using advanced techniques like Convolutional Neural Networks (CNNs). The primary goal is to develop a robust system capable of effectively detecting and distinguishing between genuine and fraudulent signatures.

## Methodology

### Dataset

The dataset used is the ICDAR 2011 Signature Dataset, consisting of genuine and forged signatures from Dutch users. Approximately 23,000 images are used for training and 5,000 for testing.

### Models Implemented

1. **Siamese Network with ResNet50**
2. **Siamese Network with MobileNetV2**
3. **VGG-16**

Each model leverages transfer learning with pre-trained architectures to enhance feature extraction and improve accuracy.

## Results

- **VGG-16** achieved the highest accuracy of 99.6%, outperforming the other models.
- **SNN with MobileNetV2** achieved an accuracy of 98.99%.
- **SNN with ResNet** achieved an accuracy of 98.05%.

Training and validation loss curves indicated effective learning and high precision in detecting forged signatures.

## Features

- High accuracy in distinguishing genuine and fraudulent signatures.
- Robust scalability with a large dataset.
- Real-time detection capabilities suitable for integration into live systems like banking and legal sectors.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Dhanu-11/Netflix-Clone.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Netflix-Clone
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

Run the main script to start the signature verification process:
```sh
python main.py
