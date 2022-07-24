# Image-Classification-on-MNIST-with-customized-ResNet-Model
This is my first image classification project!
I customized ResNet18 input layer to accept Grayscale images (of dimension 1), and changed output classes to 10 to fit in MNIST dataset.
Then I trained using batchwise gradient descent. Training dataset was converted to batches of 60 images and passed through training loop 15 epochs to optimize the weights.
Crossentropyloss was used to calculate loss
SGD or stochastic gradient descent optimizer was used with learning rate of 0.001 and modulation of 0.9. Modulation helps in faster convergence.
The loss function significntly reduced from 2 to 0.001.
To rule out overfitting, I tested model by testdataset of 10000 images and resulting accuracy was 98%. This showed trained model is well able to generalize.
