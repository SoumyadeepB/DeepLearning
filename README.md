<h1 align="center"> Deep Learning </h1>

All Projects and Coursework related to Deep Learning:  

### 1. Age-Regression:  
The task is to infer the age of a person given a potrait picture of him or her. Intuitively this task seems to be easy at first, you are shown a potrait of a person and need to estimate his or her age. But implementing such an estimator on a computer is rather challenging. If you want to use a model based machine learning algorithm, you would need some sort of model or set of rules, which maps the raw pixel values of an image to an estimated age. This would require a lot of expert knowledge and feature design. Fortunately we can use neural networks to learn such a mapping directly from annotated examples, i.e. potraits labeled with the age of the person in the picture. In this way we just need enough examples and don't have to design the probably very complex mapping from pixels to age ourselves.  

 ![AgeRegression](https://user-images.githubusercontent.com/12089275/90393239-a23c6180-e090-11ea-91b8-d5e0176de857.png)


### 2. Classification Task:
The task is to classify a handwritten digit, the labels y for each image are from the set {0,1,...,9}. The FashionMNIST data set is very similar to MNIST it also has approximately the same number of images with exactly the same dimensions as MNIST. It was provided by Zalando research and contains 10 classes of different fashion objects.

 ![Classification_task](https://user-images.githubusercontent.com/12089275/90393243-a4062500-e090-11ea-9315-0faa79b62a39.png)


### 3. RNN Text Classification:
This text classification project trains a recurrent neural network on the IMDB large movie review dataset for sentiment analysis. It classifies movie reviews as positive or negative using the text of the review. So, this is an example of utilizing RNNs for binary classification.
We'll use the IMDB dataset that contains the text of 50,000 movie reviews from the Internet Movie Database. These are split into 25,000 reviews for training and 25,000 reviews for testing. The training and testing sets are balanced, meaning they contain an equal number of positive and negative reviews.


### 4. Deep Convolutional Generative Adversarial Network (DC-GAN): 
In this project, we create a miniature Deep Convolutional Generative Adversarial Network (DC-GAN) framework for the generation of MNIST digits. The goal is to bridge the gap between the theoretical concept and the practical implementation of GANs.

![alt-text](https://github.com/SoumyadeepB/DeepLearning/blob/master/DC_GAN/dcgan.gif)
