# Alzheimer-s-Disease-Detection-Using-VGG-19
This repository contains a Jupyter notebook implementing a deep learning model to detect Alzheimer's Disease using the VGG-19 architecture. 

The model utilizes transfer learning, applying the VGG-19 model pre-trained on ImageNet to a specific dataset of brain images classified into categories based on the stage of Alzheimer's Disease. The notebook includes:

- Data preprocessing and augmentation steps using TensorFlow's ImageDataGenerator for effective model training.
- Construction and training of the VGG-19 model with fine-tuning for the task at hand.
- Evaluation metrics such as confusion matrices and classification reports to assess the model's performance on the test dataset.
- Visualization of training and validation loss and AUC (Area Under the Curve) to monitor model learning over epochs.

This project aims to leverage advanced neural network capabilities to aid in the early detection of Alzheimer’s Disease, potentially contributing to better patient outcomes through earlier intervention.

# Key Features:

- Use of TensorFlow and Keras for building and training the neural network.
- Application of transfer learning to adapt a robust pre-existing model (VGG-19) to a specialized medical imaging task.
- Detailed performance analysis using confusion matrices and classification reports.
- Visualization of model training progress with loss and AUC graphs.

# Usage:
The notebook is designed to run in a Google Colab environment with data hosted on Google Drive, ensuring easy access and scalability. Users can train the model with their own Alzheimer's Disease image datasets by adjusting the paths and parameters as necessary.


Dataset Link: https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images

