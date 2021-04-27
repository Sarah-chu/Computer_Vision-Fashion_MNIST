# Computer Vision - Fashion MNIST

This is a self-assessment on building Convolutional Neural Network using **Keras** and the built-in Fashion MMIST dataset.

## Dataset

The built-in Fashion MNIST dataset will be used in this mini-project. This dataset includes 10 labels of different clothing types with 28 by 28 *grayscale* images. There is a training set of 60,000 images and 10,000 test images.

    Label	Description
    0	    T-shirt/top
    1	    Trouser
    2	    Pullover
    3	    Dress
    4	    Coat
    5	    Sandal
    6	    Shirt
    7	    Sneaker
    8	    Bag
    9	    Ankle boot
    
    
## Convolutional Neural Network

### The CNN consists of the following layes : 

* 2D Convolutional Layer, filters=32 and kernel_size=(4,4)
* Pooling Layer where pool_size = (2,2)

* Flatten Layer
* Dense Layer (128 Neurons), RELU activation

* Final Dense Layer of 10 Neurons with a softmax activation

* Parameters: loss='categorical_crossentropy', optimizer='adam', metrics=['accuracy']

## Result

The model achieves 91% accuracy which means it can correctly identify the class of 91% of images.
