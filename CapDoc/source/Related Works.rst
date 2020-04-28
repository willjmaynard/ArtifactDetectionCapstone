Related Works
=============

Classification of Blurred and Non-Blurred Images [3]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

There is a 2018 github project that uses Laplacian and a Convolutional Neural Network (CNN). They used the CERTH Image Blur Data set. The dataset consists of undistorted, naturally-blurred and artificially-blurred images for image quality assessment purposes. The dataset they used is available at: http://mklab.iti.gr/files/imageblur/CERTH_ImageBlurDataset.zip.
Their Project yielded a CNN accuracy of 67.70%, and a Laplacian Accuracy of 63.58%.

DeepFocus: Detection of out-of-focus regions in whole slide digital images using deep learning [1]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

We primarily built our Convolutional Neural Network (CNN) based on the studies of
DeepFocus.  The DeepFocus CNN architecture consists of five convolution layers, three max-pooling layers (after the third, fourth and fifth convolution layers) and fully connected layers. The last layer of the CNN in DeepFocus is a softmax, which results in a probability of a tile belonging to either of the two classes.

They used accuracy to evaluate their CNN; they tested their CNN on 6 Whole Slide Images, and achieved the following average accuracies:

Slide 1: 85.4%
Slide 2: 99.5%
Slide 3: 99.2%
Slide 4: 83.2%
Slide 5: 99.7%
Slide 6: 92.2%
