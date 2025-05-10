# Vehicle Image Classifier
This is a mini data science project i made using deep learning for image classification.

## Overview
In this project, I built a Vehicle classifier that could identify 17 different vehicle types. This could be useful for transportation or any other industries that need to automatically categorize vehicles into types (Car, Bus, Truck, etc).
A vehicle could be captured by a camera and information about the vehicle could be shown. This project is the underlying model for building something with those capabilities. 

I was able to get my model to predict the vehicle type with a 95% accuracy after minimal tuning. This result was achieved by using transfer learning on a CNN that is trained on resnet34. 

![alt text](https://github.com/IssabelAverina/PersonalProjects/blob/c0a978fd6c54ad06bb1e6f0874ec0bffad894264/VehicleClassifier/vehicleMatrix.png)

## Notes
- This model was made using google colab with fastai deep learning library
- The data was manually collected with the help of a chrome extension [FatKun Batch Download Image](https://chromewebstore.google.com/detail/mojcdcedhidldcgaokbelcmffoaengkj?utm_source=item-share-cb)

