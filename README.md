# Face-Mask-Detection
 Face Mask Detection From Images Using Mobilenet
 
### This project is aimed to develop an application that can detect whether a person is wearing a face mask or not. 

### Introduction
The objective of this project is to develop a face mask detection system using convolutional neural networks (CNNs). Face masks are worn by people to protect themselves and others from the transmission of respiratory infections. However, the use of face masks has been shown to vary widely in different settings. In some cases, face masks are not used at all, while in others, they are used inconsistently. This can lead to a lack of protection against respiratory infections.
 
## Dataset

The dataset used to train the face mask detection system is the "FaceMask Dataset Covid-19(10k Images 2 Folders)" dataset from Kaggle (https://www.kaggle.com/datasets/muhammadahsan026/facemask-dataset-covid1910k-images-2-folders). The dataset consists of 10K images of faces, with and without masks.

<img src="img/Img-grid.png">

### Methodology

The face mask detection system was developed using convolutional neural networks (CNNs). CNNs are a type of artificial neural network that are well-suited for image classification tasks. The system was trained on a dataset of images of people wearing face masks in different settings. The system was then tested on a separate dataset of images to evaluate its performance.
In this project, I have implemented a Mobilenet convolutional neural network that takes an image of a person's face and predicts whether the person is wearing a mask or not. 

The input image is a color image with dimensions of 100x100x3. The output of the neural network is a  prediction probability.

In this i used a Mobilenet Neural Netowork without pretraining weights. The first 11 layers are depthwise separable convolutional layers with 3x3 kernels. The final layer is a 1x1 convolutional layer with a sigmoid activation. 

### Dataset Preprocessing

The first step in any machine learning project is to preprocess the data. This dataset is already in a good format for training a CNN. However, there are a few steps that will be taken to improve the results.
  - Rescale Image
  - Resizing images into 100*100
  - Prepare Train and Validation set
  
 ### Training Convolutional neural network
 
There are many ways to train a convolution neural network. One common method is to use a training set and a validation set. The training set is used to train the network, and the validation set is used to evaluate the performance of the network.


## The project is developed using the following tools and libraries:
- TensorFlow 2.0
- Keras
- NumPy
- Opendatasets
- Pillow
- Gradio
- matplotlib

## Gradio Deployed Model Screenshot

<img src = "img/Gradio-dash.png">
