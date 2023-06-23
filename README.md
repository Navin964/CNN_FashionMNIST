## Fashion MNIST Image Classification
This project is an implementation of image classification using the Fashion MNIST dataset. The goal is to classify images of various clothing items into their respective categories.

### Dataset
The Fashion MNIST dataset is used for training and evaluation. It consists of 60,000 training images and 10,000 testing images. Each image is a grayscale 28x28 pixel image, representing a clothing item from one of the following categories:

* T-Shirt/Top
* Trousers
* Pullover
* Dress
* Coat
* Sandal
* Shirt
* Sneaker
* Bag
* Ankle boot

### Prerequisites
Make sure you have the following libraries installed:

* TensorFlow
* Pandas
* NumPy
* Matplotlib

### Code Explanation
* Imports: The necessary libraries and modules are imported for the project.

* Load the Data: The Fashion MNIST dataset is loaded using TensorFlow's built-in dataset. It is divided into training and testing sets.

* Reshape the Data: The input images are reshaped to match the model's input shape.

* Number of Classes: The number of unique classes in the dataset is determined.

* Build the Model: The model architecture is defined using the functional API of Keras. It consists of convolutional layers, followed by flattening, dropout, and dense layers.

* Compile and Fit: The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss. It is then trained on the training data for a specified number of epochs.

* Plot Accuracy and Loss: The training and validation accuracy and loss values are plotted.

* Label Mapping: A list of class labels is created for reference.

* Prediction and Visualization: The trained model is used to predict labels for the test data. Some misclassified examples are randomly selected and displayed with their true and predicted labels.

### Results
The accuracy and loss curves are plotted during the training process. Additionally, some misclassified examples are shown to analyze the model's performance.
