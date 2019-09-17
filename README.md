# DL4NLP-1st-Assignment
Logistic Regression Classifier

In this assignment we implement a logistic regression classifier for this [dataset] (https://www.kaggle.com/iarunava/imdb-movie-reviews-dataset) from scratch.

### Data prepration 
The dataset has test and train splits but for research purposes we used part of the training data as validation. So, after splitting we have the following parts:

  Train: 20000 
  Validation: 5000
  Test: 25000

We also used a feature vector with 2000 features for each of the sentences as a representation.

### Model parameters
The model default parameters are set as follows but you can easily changed the parameters by creating a new instance of logistic_regression and pass the parameters to it when initializing.
  Learning rate: 0.1
  Batch size: 20
  Number of epochs: 300
  
### How to use the code
Here is the view only [link](https://colab.research.google.com/drive/1tNh3vXd-0XSACaj3WrL2Jx0WvAVYwkTO) to the colab notebook. Also, by clicking on the ".ipynb" file up there you can see the code and a runtime of it which I ran before.
