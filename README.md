# Computer-vision

Project name: Handwritten digits classifier from the scrach by using Neural Networks and Pytorch

Dataset Downloading
Before downloading the data, I have used transformations to perform on the data before feeding it into the pipeline.

1.transforms.ToTensor():- converts the image into numbers, that are understandable by the system. Basically it Convert a PIL Image or numpy.ndarray to tensor. (https://pytorch.org/vision/stable/transforms.html).

2.transforms.Normalize():- normalizes the tensor with a mean and standard deviation.(https://pytorch.org/vision/main/generated/torchvision.transforms.Normalize.html)



Using Neural Networks
In this project I have tried to apply basic neural network for computer to identify handwritten digits. While more modern neural networks can do a much better job at tasks like this, the network above is simple enough for us to understand exactly what it’s doing and how it was trained with almost no background. 
Somehow identifying digits is incredibly easy task for our brain to do, but almost impossible to describe how to do. The traditional methods of computer programming, with if statements and for loops and classes and objects and functions, just don’t seem suitable to tackle this problem.


The Structure of a Neural Network
Here is thing that holds a number Specifically, a number between 0.0 and 1.0 called neurons. Neural networks are really just a bunch of neurons connected together.
