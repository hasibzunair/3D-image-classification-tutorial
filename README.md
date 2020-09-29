## The [notebook](https://keras.io/examples/vision/3D_image_classification/) is now available at the Keras documentation!

# A tutorial notebook on 3D image classification

Train a 3D convolutional neural network to predict presence of pneumonia.

## Dataset

I used a subset of the dataset by [MosMedData: Chest CT Scans with COVID-19 Related Findings](https://www.medrxiv.org/content/10.1101/2020.05.20.20100362v1) which consists of 200 3D CT scans in total for the two classes. 

## What is it about?

This example will show the steps needed to build a 3D convolutional neural network (CNN) to predict the presence of viral pneumonia in computer tomography (CT) scans. 2D CNNs are commonly used to process RGB images (3 channels). A 3D CNN is simply the 3D equivalent: it takes as input a 3D volume or a sequence of 2D frames (e.g. slices in a CT scan), 3D CNNs are a powerful model for learning representations for volumetric data.

## Usage

You can run the entire notebook on Colab! Copy the [URL](https://github.com/hasibzunair/3D-image-classification-tutorial/blob/master/3D_image_classification.ipynb) of the notebook [here](https://colab.research.google.com/github/). 
