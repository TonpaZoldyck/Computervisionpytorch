
# Project Summary: Image Recognition with PyTorch

## Introduction

In this project, I embarked on a journey into the fascinating world of computer vision and image recognition. Leveraging the power of PyTorch, I set out to build a robust image classification model capable of distinguishing between two distinct datasets: the Fashion MNIST dataset and the MNIST dataset.

## Dataset Overview

The project began with a careful examination of the two datasets. The Fashion MNIST dataset consisted of grayscale images of fashion items, while the MNIST dataset contained handwritten digits. These datasets served as the foundation for our image recognition task.

## Data Preprocessing

Before diving into model development, extensive data preprocessing was necessary. This involved tasks such as resizing the images to a uniform size, normalizing pixel values, and splitting the data into training and testing sets. Data augmentation techniques were also employed to enhance the model's ability to generalize.

## Model Architecture

The heart of this project was the convolutional neural network (CNN). I designed a custom CNN architecture tailored to the nature of the datasets. The network consisted of multiple convolutional layers followed by max-pooling layers, which allowed the model to capture hierarchical features present in the images. These layers were followed by fully connected layers leading to the output layer, where class predictions were made.

## Training and Evaluation

The training phase involved optimizing the model's weights using stochastic gradient descent. During training, I closely monitored key metrics such as loss and accuracy to ensure the model's convergence. Early stopping techniques were applied to prevent overfitting.

Once trained, the model was evaluated on a separate test dataset to assess its performance. Classification accuracy, precision, recall, and F1-score were computed to gauge the model's ability to correctly classify images.

## Results and Insights

The image recognition model demonstrated impressive performance. It achieved high accuracy on both the Fashion MNIST and MNIST datasets, showcasing its versatility in handling different image recognition tasks. Visualizations of the model's predictions were created to gain insights into its decision-making process.

This CNN model was the best performer, as we can see from the below it classifed most of the items correctly to a high accuracy level.

![Confusion Matrix](Compvision_conf_mat)

We note that the items it struggled with were such as t-shirt and shirt, given the image colour and qualiy it makes sense why this was a diffuclt item to match. 

Overall I was able to tune the CNN algorithm to get a accuracy of 88% and out perform the standard linear and non-linear neueral Neaural networks I used as a baseline.

## Conclusion

This image recognition project illuminated the power of PyTorch and deep learning in solving complex computer vision problems. By successfully creating a CNN model capable of distinguishing between fashion items and handwritten digits, it opened doors to a wide range of applications, from e-commerce to digit recognition in various domains. The project underscored the importance of preprocessing, model architecture, and rigorous evaluation in building
