# HandWrittenDigitRecognition

This is a Neural Network (NN) that can recognize hand-written digits in the range [0, 9]. 

The model is trained using MNIST database, which consists of 60000 training data and 10000 for model testing. Data are reshaped properly to be accepted by tensorflow.

The NN has three layers of (25, 15, 10) units, respectively, with ReLU activation functions for the hidden layers. This model can be varied to appreciate the change in performace: in particular the evolution of the loss function and the accuracy of the model are displayed. Furthermore, there is a function that counts the errors in the test dataset.
