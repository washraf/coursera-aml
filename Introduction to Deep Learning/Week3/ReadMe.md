# Introduction to CNNs
## Motivation for CNNs
* Definition CNNs
* Bp for CNNs
## First CNN
* Trainable Parameters count
* Receptive fields
* Pooling Layer
* Back propagation for Pooling layers

# Modern CNNs
## Training Tips
* Activation Functions
    * Sigmoid
    * Tanh
    * ReLU: Problem of Dying activation 
    * Leaky RelU
* Weights Initializations: Issues with Random Initializations
    * Xavier Initializations ![Xavier](https://latex.codecogs.com/gif.latex?%5Csqrt%7B2%7D/%5Csqrt%7Bn_%7Bin%7D&plus;n_%7Bout%7D%7D)
    * ReLU Initializations ![ReLU](https://latex.codecogs.com/gif.latex?%5Cinline%20%5Csqrt%7B2%7D/%5Csqrt%7Bn_%7Bin%7D%7D)
* Batch Normalization
* DropOut
* Data Augmentation: Applying distortions to expand the data set
## Examples
* AlexNet (2012)
* VGG (2015)
* Inception V3 (2015)
* ResNet (2015)

# Applications of CNNs
## Transfer Learning
* Reusing Features
* Fine Tuning instead on Random Initialization
## Other Tasks
* Semantic Segmentation
    * classify each pixel
    * Un Pooling
* Classification and Localization 