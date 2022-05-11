# CPTS_534-Neural-Network-Design-and-Application
Code for Neural network project

The purpose of this project is to adress a real-world problem and apply techniques learned in this class to solve the addressed problem. 

In this project I have created and trained two models.
1. Baseline: A baseline is a model that is both simple to set up and has a reasonable chance of providing decent results. Baseline is important, because it gives us a intuition for how easy or hard the problem you are solving is. Intuitively, baselines give lower bounds on the performance a regular model will obtain. Here, the baseline model was built using simple CNN-RNN model with decent accuracy.
2. Proposed Model: Here a new model is built which is a development over the baseline. This model uses a technique called attention mechanism. Attention mechanism is a technique where a decoder utilizes the most relevant part of the image in a flexible manner. 


Using appropriate evaluation metric, we evaluate the accuracy of both baseline and proposed model and perform error analysis that helps us get results and some useful insights.




## Introduction
We know how easy it is for our minds to tell what a given image is about, but can a computer tell what the image is representing? Computer vision researchers worked on this a lot and they considered this impossible till now! With the help of deep learning techniques, availability of huge datasets and computer power, we can build models that can generate captions for an image.

In this project we will see a Image Caption Generator which is a challenging Neural Network problem where a textual description must be generated for a given photograph. It requires both methods from computer vision to understand the content of the image and a language model from the field of natural language processing to turn the understanding of the image into words in the right order. The primary aim would be to build a Network model that would generate captions for an input image which explains the context of the image. To build the model, we will use basic Neural Networks such as Convolutional Neural Networks and LSTMs (a type of Recurrent Neural Network) along with a technique called attention mechanism which recently played an important role in computer vision and is recently widely used in image caption generation tasks.
