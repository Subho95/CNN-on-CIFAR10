# CNN-on-CIFAR10
A classification model has been build using Deep Convolution Neural Networks for performing classification on CIFAR10 dataset. The data set consists of 10 classes and 10000 data items for testing and 50000 data for training. Each data is a 32x32x3 array which represents a picture and lebeled in 0-9 range. Our model consists of 4 conv layers with 3x3 kernel with maxpool associated with each of them. The activation ised is relu. Dropout is also used to prevent overfitting. At the end of conv layers, 4 dense layers are added with proper dropouts and relu activation. Finally a softmax activation layer is added to get the probability.  

Requirements:
1. sys
2. Tensorflow version 1.x
3. matplotlib inline
4. pickle
5. numpy
6. os
7. sklearn
