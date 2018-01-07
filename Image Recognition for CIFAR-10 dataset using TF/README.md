# CNN-Project #

## DATA
We will be performing image recognition using the CIFAR-10 dataset.  
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.    
The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.  

## NOTES
Used two Convolution Layers and one final full layer.  
Employed drop-out mechanism with a holding probability of 50%.  

## CONCLUSION  
Obtained an accuracy of 70% when trained over 5000 images.
