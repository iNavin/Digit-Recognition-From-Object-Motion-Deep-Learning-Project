# Digit-Recognition-From-Object-Motion-Deep-Learning-Project

This project is all about hand movement (Gesture) tracking and its recognition,
 In this we will be developing an algorithm which analyses sequential video frames and outputs the movement of target ( in our case which will our hand or fingers) between the frames 

The User  will now be able to gesture  a digit using his hand motion and the system will be able to recognize the digit gestured by the user , the recognition will be powered by Neural Network using Softmax Regression

# Proposed Algorithm / Methodology:

For motion detection through the camera, we are using the libraries in computer vision (OpenCV). This library also enables detection, conversion, comparison and other operations to be performed on the images and frames captured by the camera.
The image frames captured will be processed by a neural network model using softmax regression for the recognition of the respective characters gestured by the user
Here the Neural network model is a supervised training model which is first trained using the MNIST dataset and then the Classification model is used for classifying real input characters from the image frames

![image](https://user-images.githubusercontent.com/41445769/219850961-0857c64a-5776-4f41-a4bd-509fcf657a79.png)

ALGORITHM :
1. Start with values (often random) for the network parameters (wij weights and bj biases).
2. Take a set of examples of input data and pass them through the network to obtain their prediction.
3. Compare these predictions obtained with the values of expected labels and calculate the loss with them.
4. Perform the backpropagation in order to propagate this loss to each and every one of the parameters that make up the model of the neural network.
5. Use this propagated information to update the parameters of the neural network with the gradient descent in a way that the total loss is reduced and a better model is obtained.
6. Continue iterating in the previous steps until we consider that we have a good model.

# Sample Results
![image](https://user-images.githubusercontent.com/41445769/219851158-43e29ffd-10fb-467e-896c-04c015eec17b.png)

