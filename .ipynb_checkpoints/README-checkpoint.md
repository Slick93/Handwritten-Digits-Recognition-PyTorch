# Handwritten-Digits-Recognition-PyTorch
The primary function of this repository is to design a neural network which detects handwritten numerical digits using PyTorch.

The popular *MNIST* dataset was used to train and test the model. The dataset contains 60,000 images for training purposes and a separate 10,000 image set for testing the designed classification model.

*PyTorch* was employed as the main tool to implement a convolutional neural network. *Adam* was used as an optimizer with agreeable results. *cuda* was also deployed to fasten the processing time through a Nvidia GPU 1660Ti model. 

In the end, over *98% accuracy* was found in the designed model over consecutive successful runs.

A confusion matrix was used to display the end results with the help of *scikit* library in Python