# Damage-detection-using-CNN

## Introduction
Welcome to the Image Detection CNN project! This project implements a Convolutional Neural Network (CNN) using transfer learning with the InceptionV3 architecture to classify images into positive and negative classes. It is designed to be a binary image classification system.

## Requirements
To run this project, you will need the following dependencies:

Python 3.x
TensorFlow 2.x
Keras
NumPy
Pandas
OpenCV
Matplotlib
You can install these dependencies using pip. For example:
### pip install tensorflow keras numpy pandas opencv-python matplotlib

# Installation
Clone the repository to your local machine:
git clone https://github.com/patllola/Damage-detection-using-CNN/

# Usage
Prepare your dataset: Place your positive and negative image samples in their respective folders. The positive images should be in the "Positive" folder, and the negative images should be in the "Negative" folder.

Adjust the paths in the code: In the script file main.py, modify the load_images_from_folder function calls to point to the correct folders on your machine:
load_images_from_folder("/path/to/your/dataset/Positive")
load_images_from_folder("/path/to/your/dataset/Negative")

Training the model: Run the main.py script to start training the CNN model on your dataset. The model will be trained using transfer learning with the InceptionV3 architecture.

Monitoring training progress: During training, the script will display example images from the dataset and show the model's accuracy on the training set. If the training accuracy reaches 99.9%, the training will be automatically stopped.

# Dataset
My Datset contains sample inages which show crack in concreate.

# Model
I have mentioned the code how to use inceptionV3 model to train with my datasets.

Results
I have showed the execution values of 4 sample of the classification of my input sample images. If their is any damage in the image the images predict the damge ratio with 99% accuracy.

# Contributing
If you would like to contribute to this project, please follow these guidelines:

# Fork the repository on GitHub.
Create a new branch for your feature or bug fix.
Make your changes and commit them with descriptive commit messages.
Push your changes to your forked repository.
Submit a pull request, and your changes will be reviewed.
# License
MIT Licence

