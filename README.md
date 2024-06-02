# Image Classification using Convolutional Neural Networks (CNN)

This Google Colab notebook demonstrates image classification using Convolutional Neural Networks (CNNs). It uses the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The classes are: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## Notebook Overview

1. **Loading and Preprocessing Data:**
   - Loading the CIFAR-10 dataset using TensorFlow Datasets.
   - Preprocessing the data by normalizing pixel values and converting labels to one-hot encoded vectors.

2. **Building the CNN Model:**
   - Defining a CNN model architecture using TensorFlow's Keras API.
   - Compiling the model with appropriate loss function, optimizer, and metrics.

3. **Training the Model:**
   - Training the CNN model on the CIFAR-10 dataset.
   - Monitoring training progress with training/validation loss and accuracy.

4. **Evaluating the Model:**
   - Evaluating the trained model on the test dataset.
   - Computing test accuracy and generating classification reports.

5. **Visualizing Predictions:**
   - Visualizing sample images from the test dataset along with their predicted labels.
   - Displaying the top misclassified images to understand model performance.

## Usage

To run this notebook, you can simply open it in Google Colab and execute each cell sequentially. Make sure to enable GPU acceleration to speed up training if available.

## Dataset Citation

The CIFAR-10 dataset was collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton. You can find more information about the dataset and its usage guidelines [here](https://www.cs.toronto.edu/~kriz/cifar.html).

## Credits

This notebook was created by [Your Name]. You can find the original notebook [here](https://colab.research.google.com/drive/1xKluf7pnLS_Ld0VWXZ3rV6CiCpVP66EL?usp=sharing).
