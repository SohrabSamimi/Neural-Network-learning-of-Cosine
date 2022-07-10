# Neural-Network-learning-of-Cosine

The code was written with the Pytorch Deep Learning library.

We train a Neural Network to learn the Cosine function.
We generate our data by working on interval [-2 ; 2] that we 
discretize uniformly using 5000 points.

We then split this data in Training Set(80%) and Test Set(20%).

We use Tanh and LeakyReLU as activation functions.

The Train Loss is around 0.01 and the Test Loss
is around 0.6 after 400 epochs.

We notice that the model performs well on the training data
but does not generalize well outside.

We show here under the curve of the cosine function and the curve of the evaluation of the learned model on
the interval [-3,3]: we see that on the training set the two
curve almost exactly agree, but not on the rest.


![cosine](https://user-images.githubusercontent.com/58103877/178149431-9e632d1c-bd5c-453f-bce6-c96223481935.png)
