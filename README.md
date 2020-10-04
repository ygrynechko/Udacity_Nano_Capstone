## Udacity's Data Scientist Nanodegree Capstone Project: Dog Breed Classifier

### Project Overview

This project uses Convolutional Neural Networks (CNNs) and transfer learning in order to build a pipeline to process real-world, user-supplied images. Convolutional Neural Networks (CNNs) are commonly used to analyse image data. Transfer learning is a technique that allows to reuse a model across different tasks. The objective is that given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. If the algorithm can't identify the image as a human or dog, it will say so.

### Table of Contents

1. [Libraries](#libraries)
2. [File Descriptions](#files)
3. [Content](#contents)
4. [Findings](#findings)

### Libraries <a name="libraries"></a>

    Keras
    OpenCV
    Matplotlib
    Numpy

### File descriptions <a name="files"></a>

* dog_app.ipynb: Jupyter notebook containing the algorithm and process used to create it.
* dog_app.html: A copy of dog_app.ipynb in html format.
* Haarcascades folder: Xml file for use with the OpenCv face detector class.
* Various images: Images in jpg and jpeg format used to test the algorithm's predictions.


### Contents <a name="contents"></a>

The project is organized along the following steps:

* [Step 0] Import Datasets
* [Step 1] Detect Humans
* [Step 2] Detect Dogs
* [Step 3] Create a CNN to Classify Dog Breeds (from Scratch)
* [Step 4] Use a CNN to Classify Dog Breeds (using Transfer Learning)
* [Step 5] Create a CNN to Classify Dog Breeds (using Transfer Learning)
* [Step 6] Write your Algorithm
* [Step 7] Test Your Algorithm

### Findings <a name="findings"></a>

* The model achieved a test accuracy of 77%, which is above the 60% established accuracy threshold.
* Model needs improvement to recognize breeds that are similar. 
* The model was not working well with pictures with a lot of noise. 
* The model would recognize only one dog breed from the picture, in the future release change it to recognize all the dogs on the picture.

### Get started <a name="Get started"></a>

git clone https://github.com/ygrynechko/Udacity_Nano_Capstone

and run dog_app.ipynb in jupyter notebook


Jupyter notebook must be installed. Python must be installed. The following python modules must be installed.

opencv-python


matplotlib

pandas

numpy

pillow

scipy

tqdm

scikit-learn

scikit-image

seaborn

h5py

ipykernel

bokeh


##The step by step project is here: https://github.com/ygrynechko/Udacity_Nano_Capstone/blob/master/dog_app.ipynb
