# Digit_Classifier
A Convolutional Neural Network using Tensorflow exploiting Back Propagation and SGD to identify handwritten digits from the MNIST dataset.

# Prerequisites
1. iPython Notebook (Jupyter preferably)
2. python packages - pip, os, numpy, scipy; standard libraries - pickle, gzip
3. Dataset gzip file.

# Dataset : http://yann.lecun.com/exdb/mnist/
Dataset imported from the MNIST database of handwritten digits. It contains a training and testing set of 60k and 10k samples of images of  handwritten digits (bilevel) size normalized to 20px*20px.

# Procedural Workflow
1. Import packages.
2. Helper function definition
3. Neural Network Class generation
4. Load MNIST image data as train, test, validation
5. Parametric SGD with n epochs
6. Validation and accuracy testing
