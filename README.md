# Shoe Pair Classification Using Convolutional Neural Networks

## Project Description
This project involves building a convolutional neural network (CNN) to predict whether two shoes are from the same pair or from different pairs. Two approaches are used in this project:

1. **CNN with Single Image Input**: Each entry in the data contains a single image showing two shoes (left and right) one above the other.
2. **CNN with Dual Image Input**: Each entry in the data contains two different images, one for each shoe.

## Table of Contents
- [Project Description](#project-description)
- [Approach 1: Single Image Input](#approach-1-single-image-input)
- [Approach 2: Dual Image Input](#approach-2-dual-image-input)
- [Sanity Check](#sanity-check)
- [Training and Parameter Tuning](#training-and-parameter-tuning)
- [Best Model and Results](#best-model-and-results)
- [Conclusion](#conclusion)

## Approach 1: Single Image Input
In this approach, the model is trained on images where each image contains both shoes from the same pair, with one shoe on top of the other.

## Approach 2: Dual Image Input
In this approach, the model is trained on pairs of images, where each image contains a single shoe.

### Generate Same Pair
![Generate Same Pair](https://github.com/omer1C/Image-classification-/assets/135855862/2af1de2a-2194-4105-82f0-1c3de3985b87)

### Generate Different Pair
![Generate Different Pair](https://github.com/omer1C/Image-classification-/assets/135855862/304c944f-9e67-4480-b395-12ae00c27590)

### Example of Shoe Pair Image
![Same Pair Example](https://github.com/omer1C/Image-classification-/assets/135855862/700126e9-4a56-4ab3-8527-4ed4cc3dc46a)

## Sanity Check
A sanity check is performed to ensure that learning has occurred by using the same data for training and validation.

![Sanity Check](https://github.com/omer1C/Image-classification-/assets/135855862/d6746509-5da6-4bc6-8dbd-d1e991ded64c)
The loss and accuracy of the training and validation data are more or less the same, indicating that learning has occurred.

## Training and Parameter Tuning
After the sanity check, the model is trained to achieve maximum accuracy by tuning various parameters such as learning rate, kernel size, batch size, number of epochs, etc.

![Training Progress](https://github.com/omer1C/Image-classification-/assets/135855862/96e3e3f1-79b1-4422-8cef-2a62492c1a4a)
Overfitting is observed at some points, but the best model is saved at each epoch.

## Best Model and Results
The best model and results achieved during training are shown below:

![Best Model](https://github.com/omer1C/Image-classification-/assets/135855862/6cee346e-08e9-43cc-bdc5-0dca24a4e98e)

## Conclusion
This project successfully demonstrates the ability to classify shoe pairs using convolutional neural networks with two different approaches. The model parameters were fine-tuned to achieve the best possible accuracy.

