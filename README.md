# IRIS CLASSIFICATION

we will be using logistic regression model and a sequential model with dense layers for this

iris classificaiton - typical machine learning classification project where we use a dataset to train the module to identify and recognise the targer from among the three species of irises

1. setosa
2. versicolor
3. virginica

## the neural network

the neural network made with tensorflow is of 4 layers

- dense layer with 128 units and relu activation
- dense layer with 128 units and relu activation
- dropout layer with rate=0.5 (to avoid overfitting)
- output layer with 3 units corresponding to the three species of iris flowers and softmax activation

uses the accuracy metric to determine how good the model is
it has a accuracy of 98.33%

and at the same time the logistic regression model used for a comparison has a score of 96.66
which uses a sigmoid function


# Future Scope
introduce a basic streamlit app that would be based on slider to input data and give the prediction on the flower
