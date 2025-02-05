# Digit Recognizer

The goal of this project is to train a neural network to identify handwritten digits between 0 and 9. The train and test sets are taken from the Kaggle competition "Digit Recognizer" https://www.kaggle.com/competitions/digit-recognizer.

# Neural Network used

We implement a simple Convolutional Neural Network (CNN) inspires from LeNet, which was developed by LeCun and al. in 1989. More precisely, our CNN consists of three convolutional layers, and three fully connected layers. The last step is a softmax function which decides between ten possible outcomes.

# Accuracy

Our neural network has an accuracy of about 99.20% on the test set provided by Kaggle. In particular, we performed a data augmentation on the training set by randomly rotating and flipping images.
