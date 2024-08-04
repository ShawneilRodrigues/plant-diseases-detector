# Plant Disease Classification

This project aims to classify plant diseases using a Convolutional Neural Network (CNN) trained on the "New Plant Diseases Dataset(Augmented)". The dataset contains images of various plant leaves with different diseases.

## Getting Started

### Prerequisites

### Dataset

Download the dataset using the following command:

### Training

The model is trained using a CNN architecture defined in the notebook. The training process is configured with the Adam optimizer and categorical crossentropy loss.

### Evaluation

The trained model is evaluated on both the training and validation sets to assess its performance.

### Saving the Model

The trained model is saved in both HDF5 and Keras formats for future use.

### Visualization

The training history is saved in a JSON file and can be used to plot the accuracy and loss curves. The notebook includes code to visualize the model's accuracy over epochs.

## Usage

To use the trained model for prediction, load the saved model and preprocess the input image accordingly.
