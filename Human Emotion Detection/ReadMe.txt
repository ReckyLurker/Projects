This is an implementation of LeNet and ResNet convolutional neural network models trained to distinguish between 3 different classes of emotions. 
"Angry",  "Happy", and "Sad". The LeNet model used step-by-step Convolution, Normalization and Pooling Layers followed by dense layers and an output layer giving the 
predicted probabilities of each of the class. The output layer uses the "SoftMax" function for its activation. In total, there are 63 million parameters in the model.

The ResNet model is an implementation of the ResNet34 model, introduced in the 2015, where the model won the 2015 ImageNet competition. There are about 21 million 
parameters in the ResNet model. After extensive training, the ResNet model gives a top - 2 accuracy of 86.34% while the LeNet model gives a top-2 accuracy of 89.11%.
