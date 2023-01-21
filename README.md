# COVID-19-Chest-x-ray-challenge

This code demonstrates how to use the Imagenet Inception_v3 model to train a convolutional neural network (CNN) for image classification. The code utilizes the Tensorflow library and its keras module to import the Inception_v3 model, load the dataset, and train the CNN model.

## Getting Started
To use this code, you will need to have the following:

A dataset of images for training and testing the model. The code assumes the dataset is stored in the /content/datasets/datasets/train and /content/datasets/datasets/test directories.
Tensorflow library and its keras module installed.

## Solution Structure
The necessary libraries are imported, and the image size for the model is defined.
The Inception_v3 model is imported with pre-trained Imagenet weights.
The layers of the Inception_v3 model are frozen to prevent them from being updated during training.
Additional layers are added to the model for prediction.
The model is compiled with a binary crossentropy loss function, Adam optimizer, and binary accuracy and false negatives metrics.
The training and test sets are created using the ImageDataGenerator class and flow_from_directory method.
The model is trained using the fit_generator method.
This is kaggle competation where I have submitted my solution. Accuracy of my model is 92.77% <br>

Prediction Screen Image:-
<div align="center">
    <a href="./">
        <img src="https://user-images.githubusercontent.com/68246393/158054937-bd28353e-74e8-46df-9124-5ee08019eb69.png" width="59%"/>
    </a>
</div> <br>

Kaggle Score:-
<div align="center">
    <a href="./">
        <img src="https://user-images.githubusercontent.com/68246393/158054843-9a0c92d6-0ff6-49c2-a394-c7953cc68260.png" width="59%"/>
    </a>
</div> <br>

## Conclusion
This code provides a solution for training a CNN model using the Imagenet Inception_v3 model and Tensorflow library. The code utilizes the flow_from_directory method for loading the dataset and the fit_generator method for training the model. With the help of this code, we can easily train a CNN model for image classification using the Imagenet Inception_v3 model.
