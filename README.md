# Fashion-MNIST-Image-Classification-Project
Review of supervised learning models for the classification of the Fashion MNIST dataset


For this project We would like to understand which algorithm out of a selected group(Logistic Regression, KNN, RandomForest, Neural Network(NN) and Convolutional Neural Network(CNN)) is the most effective in predicting items from our input dataset


# Data set 

Fashion MNIST data-set consists of a training set of
50000 images, validation set of 10000 and a test set of
10000. Each example is a 28x28 gray-scale image, associated
with a label that ranges between 10 different classes
consisting in types of clothing such as shoes, t-shirts,
dresses, sandals and more. The data-set intended to serve
as a replacement of the MNIST data-set used for benchmarking
machine learning algorithms, since it is possible to
routinely achieve error rates of 10 % or less

# Pre processing

After loading the dataset, the first aspect to notice is that
all the images are pre-segmented, meaning that every image
contains a single piece of clothing, all have the same square
size of 28*28 pixels.
Pixel value is a single value between 0 and 255 due to
the images being gray scale ranging [0,1], which ensures
that each pixel has a similar data distribution. Data normalization
was carried out by subtracting the mean from each
pixel and then dividing the result by the standard deviation.
Data augmentation was also implemented which is done by
altering images in the dataset.


# Tested models


- Logistic Regression 
- KNN (varying k (5,7))
- Random forest (max_depth = 70, 80)
- Linear Neural network
- CNN (single conv2d layer)
- CNN (Three layers)
- CNN (Four layers) 
