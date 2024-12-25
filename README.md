# CNN-classification
This example reports a CNN-based five-categorization task, and the details of the classification are given below:
(1) The CNN used has 4 convolutional layers, 3 average pooling layers, and 2 fully connected layers. Each layer is described in detail in the code file named "CNN.m". The files named "activations_conv.mat", "activations_pool.mat", and "startup.m" are the configuration files needed to run the CNN.
(2) The file name "Data.xlsx" is the sample data to be classified, and has 540 sets of data, including 450 sets of training data and 90 sets of testing data.
(3) The final classification result is as high as 90% (with slight variations in each classification) and can be found in file named "CNN_output.xlsx". The file named "myCNNmodel.mat" is the network structure data saved at the end of the CNN running.
