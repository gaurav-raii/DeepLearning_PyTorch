# Image-Classifier-using-Pytorch
* A Deep Neural network was employed using Pytorch framework to classify among 28 X 28 grayscale images of clothing accessories. 
The network employed has input layer with 784 units, 3 hidden layers with sizes 256,128,64. The output layer is a softmax layer having 10 units.
* The network was trained with a batch size of 64 images for 10 epochs on whole training set.
* The Adam's optmizer was used with a learning rate of 0.003.
### Labels
Each training and test example is assigned to one of the following labels:

| Label | Description |
| --- | --- |
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

# Dropout Regularization on Image Classifier Deep Neural Network model
* A second notebook called Inference and Validation has the same classifier from the first part but in this part dropout regularization has been employed to prevent the Neural network to overfit the training data also it has been validated and training and validation losses were plotted for the regularized as well as un regularized model.
* The Dropout rate was 0.2 (i.e 20 % of the weights were randomly assigned to zero)

# Saving and Loading model weights.
* A third notebook named saving and loading model weights has the code to show how the weights of model which we developed in the last notebook can be saved once the model is trained and how those values can be updated to the model directly without training the model again. This is a very useful technique since training a model again and again everytime we want to use the model for prediction is inefficient.

# Loading Image Data
* A fourth notebook contains the code to preprocess and load the image data using pytorch before using it for training our model.
