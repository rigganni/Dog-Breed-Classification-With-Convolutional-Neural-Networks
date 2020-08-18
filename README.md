[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## CNN Dog Classification

Given an image of a dog, a Convolutional Neural Network is used to estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.

![Sample Output][image1]

This repo is an exploratory analysis of state-of-the-art CNN models for classification and localization. Each model has its strengths and weaknesses.

### Installation

1. Clone this repository:

   `git clone git@github.com:rigganni/Dog-Breed-Classification-With-Convolutional-Neural-Networks.git`

	
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
4. Make sure you have already installed the necessary Python packages according to the README in the program repository.
	
