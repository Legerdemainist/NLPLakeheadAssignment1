# Convolutional Approach to Houseing Price Regression

Machine  learning tasks can usually be categorized into two main groups, classification and regression. Classification describes the more straight forward approach of determiningthe class of a certain input. These classifications can be verysimple binary classification of for  example cats and dogs or more complex multi-class classification with multiple possible categories. Regression differs from classification in the way that the end goal usually represents any real value and is not limited to acertain number of classes. Regression usually revolves around predictions, for example stock predictions or sales predictions.

## Data Set overview
The dataset used is a modified version of the California Housing Prices dataset, modified by 'Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow'.


Sample graph of the first 10 entries of the data set used.

### Final Model

The basic model that was first used consisted of a six (6) layer CNN. The first layer was a one dimensional convolution layer with 64 channels and a kernel size of one. This was followed by a Max-Pooling layer and another convolution layer with the same kernel size but 128 filters. These convolution layers were then followed by the flatten layer and two dense layers. The first dense layer consisted of 64 neurons and the second was the output layer, meaning it only had a single neuron.

The final model only consists of two convolution layers as well as a single max-pooling layer. In addition, two batch normalization layers were added as well as four additional fully connected layers

```
Give examples
```

## Test Results
Explain how to run the automated tests for this system


## Authors

* **Tim Heydrich** - *Initial work* - [legerdemainist](https://github.com/legerdemainist)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.


## References
A. Fisher, “2 multilayer 1d conv network in pytorch.”
