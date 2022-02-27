# ML-Cats-and-Dogs-Kaggle

Get my notebook: https://colab.research.google.com/drive/1ssrtQLoWnfI-jfc_S_TZgiJWyDkYEYVS?usp=sharing

I. Introduction: Research Question and Problem for Management

The cats and dogs dataset consists of images of either cats or dogs. The training set contains 25,000 images (half of which are dogs and half are cats) and the test set contains 12,500 images. The goal is to build a model that is able to recognize the cat images from the dog images and properly label them as a cat (0) or dog (1). This information will be helpful for companies that would like to begin work in image recognition. 

II. Analysis of Dependent Variable (label - cat or dog image)

An initial analysis of the dependent variable 'label' shows that this data consists of 25,000 images. Of the training set, half of the images are labeled as dogs and half the dataset images are of cats. The test dataset has 12,500 images that need to be properly labeled as either cat or dog, represented by 0 or 1 respectively. 

![image](https://user-images.githubusercontent.com/97359451/155898891-7d2e15a2-06a1-4979-93a8-6f848b151855.png)
Figure 1. First 9 images of dogs from the training dataset.

![image](https://user-images.githubusercontent.com/97359451/155898905-c6183516-ced5-43b3-a5a8-07b10d8e607c.png)
Figure 2. First 9 images of cats from the training dataset.


III. Models

The model was built with hyperparameter tuning using tensorflow keras models convolutional 2D and maxpooling 2D. Relu activation was applied to these layers and built up with a model compiler. The models were only achieving a 51.7% accuracy, and when used on the test dataset there was a log loss of 17.5. Further models will be tested to improve prediction capability.


IV. Conclusions

After hyperparameter tuning of the convolutional neural network model, there was still a log loss of 17.5. Therefore, further tuning needs to be performed in order to increase accuracy and predictive power of the model. Analysis of images and image recognition through neural networks are an important part of deep learning, and many companies will find value to this type of modeling. 
