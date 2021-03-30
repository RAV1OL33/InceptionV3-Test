# InceptionV3 Test
Keras implementation of InceptionV3 convolutional neural network in solving binary classification problems.

In current state in current state requires at least 1k pics for each category in  test and validate directory.
```
data/
    train/
        dogs/
            dog000.jpg
            dog002.jpg
            ...
            dog999.jpg
        cats/
            cat000.jpg
            cat002.jpg
            ...
            cat999.jpg
    validation/
        dogs/
            dog1000.jpg
            dog1001.jpg
            ...
        cats/
            cat1000.jpg
            cat1001.jpg
            ...
```
You can find them [there](www.microsoft.com/en-us/download/details.aspx) in microsoft download section
Use pip install -r requirements.txt to install dependencies

Ordering:
 -bottleneck_features.py: Fetching the bottleneck features from pretrained InceptionV3 as numpy arrays;
 -top_model.py: Training FFN model with numpy arrays;
 -complete_model.py: Training the complete model with images;
 -visualization.py: Visualize the result.
 
This code has been successfully tested on:
Windows 10, Anaconda3, Keras 2.4.3, tensorflow 2.3.0
