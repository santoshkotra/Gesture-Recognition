# Gesture-Recognition
Gesture Recognition using Deep Learning

# Problem Statement
Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

Thumbs up: Increase the volume
Thumbs down: Decrease the volume
Left swipe: 'Jump' backwards 10 seconds
Right swipe: 'Jump' forward 10 seconds
Stop: Pause the movie
Each video is a sequence of 30 frames (or images)

# Dataset:
The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use.
Each video is a sequence of 30 frames (or images). 
The data is in a zip file. The zip file contains a 'train' and a 'val' folder with two CSV files for the two folders.

# Objective :

Generator -  Write code for generator function so, that it can provide data in batch while training model. Also, write code for preprocessing image files in generator function Model Create models with two architectures Convolution 3D Convolution 2D + RNN a. RNN with LSTM b. RNN with GRU Output Tune model to achieve good accuracy on train as well as validation data Provide all metric with changes done in model to tune it in the write up

Dataset was provided by institute. Hence, i cannot share it here. But you can try this notebooks with any dataset that having criteria listed below:

Each video is a sequence of 30 frames (or images). all images in a particular video subfolder have the same dimensions different videos may have different dimensions. Specifically, videos have two types of dimensions - either 360x360 or 120x160 There are two csv(one for train, one for validation) files having path of videos

Link is here : https://drive.google.com/file/d/1ehyrYBQ5rbQQe6yL4XbLWe3FMvuVUGiL/view

