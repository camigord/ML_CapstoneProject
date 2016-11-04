# Deep Learning Capstone Project
## Udacity - Machine Learning Nanodegree - Capstone Project 

This is my capstone project for the Udacity Machine Learning Nanodegree. I implemented an application which detects, localizes and interprets number strings in real-world images.

![model](assets/Sample1.png)

A [report](https://github.com/camigord/ML_CapstoneProject/blob/master/Capstone%20Project.pdf) describing the development of the current project can be found together with the code.

I used [TensorFlow](https://www.tensorflow.org/) to train the model, and [OpenCV](http://opencv.org/) to capture webcam frames.

All the code was implemented as Jupyter Notebooks (Python 2.7). The following is a description of each one of the available files:

- *1_CreateSyntheticData.ipynb:* 
> Generates Synthetic training samples by concatenating digits from the [MNIST](http://yann.lecun.com/exdb/mnist/) dataset. The code assumes that TensorFlow is installed and loads the data from its tutorials.

- *2_TrainSyntheticModel.ipynb*
> Trains an initial and very simple convolutional model using the previously generated synthetic images.

- *3_Preprocess_SVHN.ipynb*
> Downloads, extracts and preprocess the [SVHN](http://ufldl.stanford.edu/housenumbers/) dataset in order to generate a more real and challenging training dataset. All the preprocessing steps are described in the [report file](https://github.com/camigord/ML_CapstoneProject/blob/master/Capstone%20Project.pdf).

- *4_TrainingOnSVHN.ipynb*
> Defines 

- *5_Generate_Regression_Datasets.ipynb*
- *6_Train_Regression_Model.ipynb*
- *7_Evaluate_Models.ipynb*
