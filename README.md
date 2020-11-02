# cifar10_resnet50



The CIFAR-10 dataset
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.


dataset link:'https://www.cs.toronto.edu/~kriz/cifar.html'





this project is an application of transfer learning for fast model processing and training.
Resnet50

In 2012 at the LSVRC2012 classification contest AlexNet won the the first price, After that ResNet was the most interesting thing that happened to the computer vision and the deep learning world.

Because of the framework that ResNets presented it was made possible to train ultra deep neural networks and by that i mean that i network can contain hundreds or thousands of layers and still achieve great performance.

The ResNets were initially applied to the image recognition task but as it is mentioned in the paper that the framework can also be used for non computer vision tasks also to achieve better accuracy.

Many of you may argue that simply stacking more layers also gives us better accuracy why was there a need of Residual learning for training ultra deep neural networks.
Problems

As we know that Deep Convolutional neural networks are really great at identifying low, mid and high level features from the images and stacking more layers generally gives us better accuracy so a question arrises that is getting better model performance as easy as stacking more layers?

With this questions arises the problem of vanishing/exploding gradients those problems were largely handled by many ways and enabled networks with tens of layers to converge but when deep neural networks start to converge we see another problem of the accuracy getting saturated and then degrading rapidly and this was not caused by overfitting as one may guess and adding more layers to a suitable deep model just increased the training error.

This problem was further rectifed by by taking a shallower model and a deep model that was constructed with the layers from the shallow model and and adding identity layers to it and accordingly the deeper model shouldn't have produced any higher training error than its counterpart as the added layers were just the identity layers.















