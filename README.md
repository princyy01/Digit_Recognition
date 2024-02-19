In this project, we propose a Convolutional Neural Network (CNN) architecture for digit recognition using the popular MNIST dataset.
The MNIST dataset consists of 28x28 grayscale images of handwritten digits (0-9) and is widely used as a benchmark dataset in the field of machine learning.

Model Architecture:
1. Input Layer: The input layer consists of 28x28 grayscale images of handwritten digits.
2. Convolutional Layers: The convolutional layers apply learnable filters to extract features from the input images. We use multiple convolutional layers with increasing numbers of filters to capture hierarchical features.
3. Pooling Layers: Pooling layers downsample the feature maps obtained from convolutional layers, reducing the spatial dimensions while retaining important information.
4. Fully Connected Layers: The flattened output from the last convolutional or pooling layer is fed into fully connected layers. These layers perform classification based on the learned features.
5. Output Layer: The output layer consists of 10 neurons corresponding to the 10 digit classes (0-9). We use softmax activation to obtain the probability distribution over the classes.

Training Procedure:
1. Data Preprocessing: Normalize the pixel values of the input images to a range between 0 and 1.
2. Model Compilation: Compile the CNN model using the Adam optimizer and categorical cross-entropy loss function.
3. Model Training: Train the model on the training set, adjusting the weights based on backpropagation and gradient descent.
4. Model Evaluation: Evaluate the trained model on a separate test set to assess its performance in terms of accuracy and other metrics.
