# neural-network

This is a neural network I made and trained from scratch for the purpose of recognizing hand drawn digits from the mnist image dataset. \
I did not use any machine learning libraries in the creation of this network (PyTorch, Tensorflow, etc.). \ \

<h1>How to use</h1> \
tl;dr clone the repo, open test.ipynb, pip install numpy, matplotlib, scipy, tensorflow (for mnist dataset), run all cells except for labeled "Tests the network" (Unless you want to see the accuracy rate for yourself!), following instructions in last 2 cells to test various images in the mnist dataset \ \


There are 2 files included in the repo: train.ipynb and test.ipynb \
train.ipynb is the code used to train the model, but the code is mostly the same as test.ipynb \
test.ipynb is for testing the model (THIS IS THE FILE YOU PROBABLY ARE LOOKING FOR). \ \



<h1>Network Architecture</h1> \
The network is composed of 4 layers of size 784 x 16 x 16 x 10 \
Layer 1 is composed of 784 neurons because each input image is 28x28 pixels (a total of 784 pixels to be used as input) \
The size of layers 2-3 are chosed arbitrarily \ 
Layer 4 is composed of 10 neurons to represent all possible outputs (digits 0-9) \ \

<h1>Training</h1> \ 
The network backpropagates through stochastic gradient descent \ \

Resources that helped me: \ 
[3Blue1Brown's Neural Network Playlist](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) \ 
[3Blue1Brown's Neural Network Articles](https://www.3blue1brown.com/topics/neural-networks) \
[Neural Networks and Deep Learning by Michael Nielson](http://neuralnetworksanddeeplearning.com/) \
[colah's blog post on Backpropagation](https://colah.github.io/posts/2015-08-Backprop/) \
