## Motivation
Since dogs have been domesticated by humans they evolved from a useful working animal to the humans best friend. 
Nowadays you'll see them in every park where humans are going for a walk with them. But don't you wonder sometimes to which breed a dog belongs? This problem could be solved by using an image classification application to predict the dog breed.

## Objectives
As part of my Data Science Nanodegree I implement such a dog breed classifier. The classifier consists of three different steps:

1. The classifier must be able to detect and distinguish between humans and dogs in images.
2. If the image contains the face of a human the breed that most resembles the human in appearance should be returned.
2. If the image contains a dog, it's breed should be returned.

## Running this project

### Libraries used

Install the following libraries to use this project:
* Keras
* OpenCV
* Matplotlib
* Seaborn
* NumPy
* Tensorflow
* glob
* scikit-learn
* Jupyter

### Datasets used

1. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dog_images.zip). Unzip the folder and place it in the repo, at location `path/to/dog-project/dog_images`. 

2. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

3. Download the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset.  Place it in the repo, at location `path/to/dog-project/bottleneck_features`.

4. Download the [ResNet-50 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogResnet50Data.npz) for the dog dataset.  Place it in the repo, at location `path/to/dog-project/bottleneck_features`.


### Running the notebook

To run the notebook simply run the cells.
To create the bottleneck features for VGG16 or ResNet-50 (if you don't want to download them) the script extract_bottleneck_features.py can be used.

## Results
Using Transfer Learning a Convolutional Neural Network has been trained to classify dog breeds achieving >80% accuracy.






