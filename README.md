In this repo, I did deep learning studies with MNIST and cat-dog datasets. 

*In the model I wrote for the **MNIST** dataset, I created a structure with 3 linear layers, with the activation function ReLu, and using log_softmax in the output layer. Since MNIST is already a child dataset, I did not use max pooling or conv layers. 

*As for the **Dog vs Cat** dataset, since this dataset is a bit more complex, I used the max pooling and conv layers. In total: There are 3 conv2d layers, 2 input and output linear layers. I logged the outputs of the model and produced the loss and accuracy graphs.