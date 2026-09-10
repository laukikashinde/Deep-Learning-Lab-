# Practical 7:  Implement transfer learning using pre-trained AlexNet, VGG16, ResNet50, and EfficientNetB0 models for image classification, and compare their performance.


## Aim

To implement transfer learning using pre-trained AlexNet, VGG16, ResNet50, and EfficientNetB0 models for image classification and compare their performance.

## Description

In this practical, transfer learning was performed using pre-trained deep learning models. AlexNet, VGG16, ResNet50, and EfficientNetB0 models trained on ImageNet were used as feature extractors. Their final classification layers were modified for the target image classification task, and the performance of the four models was compared.

## Tools and Technologies Used

* Google Colab
* Python
* PyTorch
* Torchvision
* NumPy
* Pandas
* Matplotlib
* AlexNet
* VGG16
* ResNet50
* EfficientNetB0

## Work Performed

* Loaded and preprocessed the image classification dataset.
* Resized and normalized the images according to ImageNet requirements.
* Loaded pre-trained AlexNet, VGG16, ResNet50, and EfficientNetB0 models.
* Used the pre-trained models for transfer learning.
* Froze the pre-trained layers.
* Replaced the final classification layers according to the target classes.
* Trained the modified classification layers.
* Evaluated each model using test accuracy and loss.
* Compared the performance of all four models using a graph.

## Result

Transfer learning was successfully implemented using AlexNet, VGG16, ResNet50, and EfficientNetB0, and their classification performance was compared based on test accuracy and loss.
