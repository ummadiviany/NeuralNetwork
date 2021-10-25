# NeuralNetwork

## Assignment1 
1. Find the feasibility of changing the activation function and apply it to the network (with
required adjustments). Analyze the performance of the network with different (at least two)
activation function for classification of linearly separable data provided with tutorial. You are
free to choose the number of epochs and other hyperparameters for training.
2. Use only first three features of every data point (dimensionality of data point=3) for
classification task and observe the classification accuracy for linearly separable data.
This part may be performed with only single activation function of your choice.


**Deliverables:**
- The colab notebook(s) downloaded in .ipynb format
- Screenshot of the training loss and testing accuracy as .png/.tiff files.

## Assignment2
Design a Convolutional Neural Network similar to what is shown in Tutorial 2. Use an extra layer
of convolution, relu, and maxpool and assess the performance on MNIST and CIFAR-10
datasets for 20 epochs. You are free to choose the learning rate and the optimiser type. Any
other parameter like kernel size, stride, etc is also entirely up to the choice of the experimenter.
CIFAR-10 dataset can be loaded similarly from PyTorch’s available functions. Check PyTorch
docs for more details.
NO NEED TO USE BATCHNORM2D. Do the experiment without that layer.


**Deliverables:**
- The colab notebook(s) downloaded in .ipynb format
- Screenshot of the training loss and testing accuracy as .png/.tiff files.

## Assignment3
Use the DCGAN architecture as shown in the tutorial and train the same architecture on
a publicly available dataset of your choice. Don’t use CIFAR or MNIST. Train it for 5
epochs. Don’t take a large dataset. Even if you select a large dataset discard some and
use a miniature version of that dataset.

**Deliverables:**
- Submit your code (colab notebook(s)) downloaded in ipynb format
- Submit screenshots of your generated fake images and the training loss of your GAN.

## Assignment4
Train the same image captioning network which is described in the tutorial video
till 5th epoch and run the inference on at least 5 more test images from any
natural image dataset using the saved model at different epochs (e.g. 1
images/epoch trained model).
Repeat the above mentioned task by using pretrained vgg network as encoder
(you can choose any vgg network) for 1 epoch and run inference on 2 images.

**Deliverables:**
- The screenshots of generated captions for 7 images with images (keep
small images).
- The screenshots of loss value after first epoch for both the trainings and
after 5th epoch for former training.
