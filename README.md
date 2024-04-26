# Histopathology Metastases Identification Classifier

## Project Overview

This repository contains the Histopathology Metastases Identification Classifier, a machine learning model designed to identify the presence of metastases in histopathology images. The model leverages convolutional neural networks and advanced image processing techniques to analyze microscopic images with high precision.

### Key Achievements

- **Advanced Image Classification**: Built a binary image classifier to identify the presence of metastases in histopathology images using an ROC curve.
- **Optimized Training Strategy**: Used a 90/10 split ratio feeding into a covet model and a 1-cycle policy to maximize training parameters selection.
- **High Accuracy**: Correctly identifies 99% of metastases from images during testing upon 57,000 evaluation images at 2.43 microns.

## Model Details

The classifier utilizes a series of convolutional layers to process the images, extracting features that are critical for identifying metastatic tissue. The model's architecture is designed to efficiently handle large datasets and achieve high accuracy through the following steps:

- **Data Preprocessing**: Images are preprocessed to enhance features, normalized, and resized to fit the model's input requirements.
- **Model Training**: Training involves a covet model enhanced by a 1-cycle learning rate policy to quickly converge to the best solution.
- **Evaluation**: Uses ROC curves to evaluate model performance, ensuring it discriminatively identifies positive metastatic cases with high reliability.

## Repository Contents

- **`histopathology.py`**: The main Python script for the metastases identification classifier. It includes the model's architecture, training process, and evaluation steps using ROC curves.
- **`MNIST-digit-recognizer.py`**: A supplementary Python script demonstrating a 3-layer feedforward neural network applied to the MNIST dataset. This script is fundamental for understanding basic neural network operations, including forward and backward propagation.

## Getting Started

### Prerequisites

- Python 3.8+
- TensorFlow 2.x
- NumPy, Matplotlib

## Contributing

Contributions to this project are welcome! You can help by:

- Improving the model's accuracy and efficiency.
- Extending the dataset with more diverse histopathology images.
- Optimizing the preprocessing and training pipelines.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- This project was inspired by significant research and advancements in medical imaging and deep learning.
- Special thanks to the open-source community for providing tools and libraries that facilitate machine learning research.

