## Image Classification Project.

In this project, I worked on classifying images from the CIFAR-10 dataset. The dataset consists of 10 different type of objects:

* airplanes
* automobile
* bird 
* cat
* deer
* dog
* frog
* horse 
* ship
* truck


I first preprocessed the images, then train a convolutional neural network on all the samples. The images need to be normalized
 and the labels need to be one-hot encoded. I have built a convolutional network model using  convolution, max pooling, dropout,
 and  fully connected layers. I have trained the model using the samples provided and calculated metrics for both test and
 training samples. At the end, I have done neural network's predictions on the sample images. 


## Install

This project requires Python 3 and the following Python libraries installed:

    NumPy
    Tensorflow

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.
Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```
ipython notebook dlnd_image_classification.ipynb
```

