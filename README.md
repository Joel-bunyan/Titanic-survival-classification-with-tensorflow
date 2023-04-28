Survival prediction of people on titanic based on their features like age and gender:

This is the first problem almost all beginners start off by doing. The project statement is to build a single neuron binary classification model that can find 
the relation between the features of a person and the chance of their survival if they were on the titanic ship.

This time we are going to use the Tensorflow library developed by Google to build a binary classification model. We are going to use 'sigmoid' function on top 
of the model output to convert the number between the range of 0 an 1 thus giving us binary output. 

First we will get the Inputs and outputs from the data, we will only extract important features and neglect useless features like name, ticketname etc.

And then after that we can simple develop a neuron with sigmoid activation function with the easy tensorflow syntax. And then we should specify some parameters 
like the type of optimizer, the loss function and the metrics.

Finally, we could train the model on the data for 500 iterations(epochs)
