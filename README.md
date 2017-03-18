# ML-dogs-vs-cats
Machine learning algorithm using CV and Kaggle's data sets to identify dogs versus cats

### Basics
1. Initializes core variables
2. Labels each image in originial dataset as 'cat' or 'dog'
3. Separates the 'train' vs 'test' data and saves the training data using numpy as 'train_data.npy')
4. Builds a convolutional neural network using TFLearn and Tensorflow and the trains the model using the training data. (If a model already exists, it is loaded)
5. A sample of 12 from the testing data is taken and results are displayed using 'matplotlib'
6. The model predicts the official testing data from Kaggle and outputs the results into a submission file

### Requirements
* curses
* cv2
* h5py
* matplotlib
* numpy
* tdqm
* tensorflow
* tflearn
