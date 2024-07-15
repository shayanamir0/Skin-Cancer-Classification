# Skin Cancer Detection using CNN

## Project Description
The aim of this project is to develop a Convolutional Neural Network (CNN) model to classify skin lesions into different categories based on the provided images. This helps in early detection and treatment of skin cancer, which can be crucial in saving lives.

## Dataset
This project utilizes the [Skin Cancer MNIST: HAM10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000) dataset, which contains a collection of dermatology images used to train models for skin cancer detection.

## Model Architecture
The model used in this project is a simple CNN consisting of the following layers:

- **Input Layer**: Takes in the image data.
- **Convolutional Layers**: Extract features from the input images.
- **Pooling Layers**: Downsample the feature maps.
- **Fully Connected Layers**: Classify the images based on the extracted features.
- **Output Layer**: Outputs the probability of each class.

![skin cancer cnn model](https://github.com/user-attachments/assets/7f493b85-ce31-4daf-87ec-b9e1aeba1501)

## Results
After training the model, the following metrics were achieved:

- **Accuracy**: 92%
- **Precision(Macro Average)**: 91%
- **Recall(Macro Average)**: 92%
- **F1 Score(Macro Average)**: 91%

These results indicate the model's effectiveness in classifying skin lesions.
