# Using Convnet as a feature extractor
---

- Using nolearn and lasagne for working with ConvNet
	- lasagne is based on Theano so GPU speedups will make a difference 
	- nolearn library is a collection of utilities around the NN packages 

- Working on MNIST dataset

- ConvNet architecture 
	- 2 convolutional layers with pooling
	- 1 fully connected layer and the output layer
	- Dropouts between some layers, dropout set at 50%

- Prediction
	- visualize the confusion matrix

- Filter visualization
	- visualize layers of ConvNet
	![1](https://raw.githubusercontent.com/sagarmk/ConvNet-as-feature-extractor/master/images/1.png) 

- Feature extraction
	- plotting the output layer activations
	- dense layer activations instead of forwarding to a classifier can be by themselves used as features on a linear classifier
	
	
	
	![2](https://raw.githubusercontent.com/sagarmk/ConvNet-as-feature-extractor/master/images/3.png) 
	![3](https://raw.githubusercontent.com/sagarmk/ConvNet-as-feature-extractor/master/images/2.png) 
