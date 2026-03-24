# face-shape-neural-network-classification-model
Deep Neural Network (DNN) and Convolutional Neural Network (CNN) were used to build a classification model for the Face Shape Dataset.

## Abstract
This paper explores the performance of Deep Neural Networks (DNNs) and Convolutional
Neural Networks (CNNs) at image data of face shape classification of female celebrities. Several
regularization techniques are implemented to understand their effects on model development.
This research uses the Face Shape Dataset containing 5,000 color images across 5 face shapes -
heart, oblong, oval, round, and square. TensorFlow and Keras are used to build the models. The
best performing model of this research has 3 convolutional / max pooling layers of different
kernel and stride sizes, L2 regularization, and a dense layer (256 nodes). It has 53% training
accuracy and 38% testing accuracy. The loss curves show an underfitting model and confusion
matrix shows an accurate classification of images to their labeled classes.

## Methods
This research is conducted using the Face Shape Dataset by Niten Lama (Niten). The dataset
consists of 5000 images of female celebrities across 5 face shapes: heart, oblong, oval, round,
and square. Each shape consists of 1000 images, 640 for training, 160 for validation and 200 for
testing. The entire dataset is split into 3,200 images for training, 800 for validation, and 1,000 for
testing. The main libraries are Tensorflow (v 2.18.0), Keras (v 3.8.0), matplotlib, and scikit-learn
libraries. In the experiments, the architecture, regularization method, data augmentation level,
optimizer and learning rate, batch size and epoch are tweaked to find a model with the best
accuracy and RMSE, and correct classification of the images with the labelled class with high F1
score.

16 models trained and compared for performance.
