# German Traffic Sign Recognition with Convolutional Neural Networks

This repository contains code for a Convolutional Neural Network (CNN) designed to recognize and classify German traffic signs using the [GTSRB dataset](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign).

## Description

This code implements a CNN using TensorFlow/Keras to classify 43 different types of traffic signs from the German Traffic Sign Recognition Benchmark dataset. The model is trained on images of traffic signs and achieves an accuracy of 97.13% on the test set.

## Features

- **Data Preprocessing**: Resizing images to 50x50 pixels, preparing training and test sets.
- **CNN Architecture**: Utilizes Convolutional layers, MaxPooling, BatchNormalization, Dropout, and Dense layers.
- **Model Training**: Trains the CNN with Adam optimizer and categorical cross-entropy loss function over 20 epochs.
- **Model Evaluation**: Computes accuracy metrics on a test dataset and generates a confusion matrix.
- **Visualization**: Plots training and validation accuracy/loss curves, as well as a heatmap of the confusion matrix.

## Instructions

1. Clone the repository.
2. Install necessary libraries and dependencies.
3. Execute the code in a Jupyter Notebook or Python environment.
4. Explore the training process, accuracy, and model evaluation metrics.

## Tags

- Traffic Sign Recognition
- Convolutional Neural Network
- Deep Learning
- TensorFlow
- Keras
- Image Classification
- GTSRB Dataset

## License

This code is licensed under [MIT License](LICENSE).

Feel free to contribute or use this code for educational or research purposes.

