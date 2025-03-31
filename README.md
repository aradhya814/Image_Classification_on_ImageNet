## Problem Statement

The objective of this project is to classify images into 200 different object categories using deep learning models. In many real-world applications—such as autonomous vehicles, medical diagnostics, and content moderation—accurate image classification is essential. However, training on large-scale datasets like ImageNet is resource-intensive. To address this, we evaluate the performance of multiple deep learning models using Tiny ImageNet, a lighter and more manageable alternative.

## Dataset Description – Tiny ImageNet

Tiny ImageNet is a smaller version of the full ImageNet dataset, specifically designed for experimentation and academic use. It includes:

200 distinct classes
500 training images per class
50 validation and 50 test images per class
Images resized to 64×64 pixels
Around 100,000 images in total

## Why Tiny ImageNet?
Tiny ImageNet provides the diversity and complexity of the full ImageNet dataset but is significantly smaller in size. It is ideal for training on limited hardware and allows for efficient testing and evaluation of deep learning models without requiring extensive computational resources.

## Project Objectives

Train and evaluate different convolutional neural network architectures on the Tiny ImageNet dataset
Compare model performance using metrics such as accuracy, confusion matrix, and ROC curve
Analyze and interpret the results to identify the most effective model
Models Used

## Three widely-used CNN architectures were selected for evaluation:

ResNet50 – A deep network using residual connections to avoid vanishing gradients
EfficientNetB0 – A model that balances performance and efficiency through compound scaling
MobileNetV2 – A lightweight model optimized for speed and mobile devices
Results Summary

Each model was trained for 15 epochs and evaluated on training accuracy:

## Model	Training Accuracy
ResNet50	82%
EfficientNetB0	72%
MobileNetV2	66%
Conclusion

ResNet50 achieved the highest accuracy among the models, demonstrating superior performance in classifying images from Tiny ImageNet. EfficientNetB0 showed balanced results, offering good accuracy with fewer parameters. MobileNetV2, while achieving the lowest accuracy, remains a strong candidate for applications where model size and speed are prioritized. These results offer a practical comparison of modern CNN architectures under a constrained dataset and provide insights into their relative strengths.

