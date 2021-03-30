# InceptionV3 Test
Keras implementation of InceptionV3 convolutional neural network in solving binary classification problems.
In current state in current state requires at least 1k pics for each category in  test and validate directory.

Use pip install -r requirements.txt to install dependencies

Ordering:
 -bottleneck_features.py: Fetching the bottleneck features from pretrained InceptionV3 as numpy arrays;
 -top_model.py: Training FFN model with numpy arrays;
 -complete_model.py: Training the complete model with images;
 -visualization.py: Visualize the result.
 
This code has been successfully tested on:
Windows 10, Anaconda3, Keras 2.4.3, tensorflow 2.3.0
