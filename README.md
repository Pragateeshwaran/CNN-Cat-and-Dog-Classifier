
# Convolutional Neural Network (CNN) for Image Classification

This repository contains a simple implementation of a Convolutional Neural Network (CNN) for image classification using TensorFlow and Keras.

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- Python 3.x
- TensorFlow
- Matplotlib

```bash
pip install tensorflow matplotlib
```

### Dataset

Download or organize your image dataset into a directory, and update the `image_directory` variable in the code accordingly.

### Installation

No formal installation is required. Just clone the repository and run the provided Python script.

```bash
python cnn_image_classification.py](https://github.com/Pragateeshwaran/CNN-Cat-and-Dog-Classifier.git)
```

## Procedure Map

1. **Import Libraries**: Import the necessary libraries for the project.

2. **Check Image Extensions**: Ensure that your image dataset contains valid image files with extensions like `.jpg`, `.jpeg`, or `.png`.

3. **Load Image Dataset**: Use TensorFlow's `image_dataset_from_directory` to load and preprocess the image dataset.

4. **Visualize Image Samples**: Display a sample of images from the dataset for visualization.

5. **Build Convolutional Neural Network (CNN) Model**: Create a simple CNN model using the Sequential API from Keras.

6. **Model Summary**: Display the architecture and parameters of the CNN model.

7. **Data Splitting**: Split the dataset into training, validation, and test sets.

8. **Compile the Model**: Configure the model with an optimizer, loss function, and evaluation metric.

9. **Model Training**: Train the CNN model on the training set, using the validation set for monitoring.

10. **Training History**: Plot the training and validation accuracy over epochs.

11. **Evaluate Model**: Evaluate the trained model on the test set.

12. **Visualize Predictions**: Generate predictions on the test set and visualize the results.
