# DNN1
Convolution on Mnist dataset with accuracy 99.09

# Convolution:
   Convolution is the process of applying series of summations of multiplications on the input layers so as to arrive at a single output layer which can be used to predict things.
 
# Filters/Kernels:
  Filters are used to extract features from our input. These filters are to be built in such a way that they extract the features we are interested in most.
  
# Epochs:
  Epochs is the number of times our network sees our image or input. As number of epochs increases, our network will be able to calculate weights more accurately. But as number of epochs increases, the time complexity will also increase.
  
# 1x1 Convolution:
  1x1 Convolution layer is useful in reducing the dimensions of our layers. If we wanted to cut down the dimensions from 32 to 10, we would use a 1x1x10 convolution layer which inturn combines those 32 channels to 10 channels.
 
# 3x3 Convolution:
  This convolution layer is the most used kernel size. It will look at 9 values of input layer at a time and combines them to a single value mapped onto our output layer. 
  
# Feature Maps:
  A feature map is simply the output layer we obtain after a convolution. It is a mapping of where a certain feature is found in our input layer.

# Activation Function:
  Activation functions are used to determine whether a neuron can be activated or not by calculating weighted sum and also adding a bias term to it.

# Receptive Field:
   The number of pixels of the input layer, a pixel in the output layer is looking at is called Receptive Field. It is local receptive field, if we consider the immediate or local layers and is global receptive field if all the layers are taken into account.
