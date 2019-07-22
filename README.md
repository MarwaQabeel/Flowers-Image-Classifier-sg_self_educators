# Flowers-Image-Classifier-sg_self_educators

### Table of Contents

1. [Recources](#recources)
2. [Installation](#installation)
3. [Project Motivation](#motivation)
4. [Files Description](#files)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Recources <a name="recources"></a>

Go through those tutorials before you start building your classifier:

• https://www.freecodecamp.org/news/how-to-build-the-best-image-classifier-3c72010b3d55/                                                • https://medium.com/@josh_2774/deep-learning-with-pytorch-9574e74d17ad


## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python, PyTorch and PIL.  The code should run with no issues using Python versions 3.\*, PyTorch, PIL.

You can run jupyter notebook to see the entire model build process, or you can run python scripts to directly train and use the model to recognize the flower image.

## Project Motivation<a name="motivation"></a>

This project is from Udacity's image classification project. It trains CNN model to classify picturesof flowers.

## Files Description<a name="files"></a>

**Image Classifier Project.ipynb** It is used to build the model using the jupyter notebook. It can be used independently to see how the model works.

**cat_to_name.json** It is used in ipynb and py file to map flower number to flower names.

**train_args.py** It is used by predict.py to enable the parameter function.

**train.py** It will train a new network on a dataset and save the model as a checkpoint. 

**predict_args.py** It is used by predict.py to enable the parameter function.

**predict.py** It uses a trained network to predict the class for an input image. 



## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Udacity for the project. You can't use this for your Udacity deep learning project. Otherwise, feel free to use the code here as you would like! 
