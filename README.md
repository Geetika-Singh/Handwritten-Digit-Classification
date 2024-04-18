# Handwritten-Digit-Classification
The MNIST data is a database of handwritten digits from 0 to 9. The database contains 60,000 28x28 grayscale images of the 10 digits, along with a test set of 10,000 images. The task is to create an ANN model for identifying the digit from the handwritten images.

The following tasks are performed:

Load the database to variable named digit_mnist using the Keras inbuilt datasets (digit_mnist = keras.datasets.mnist) <br>
Import data to create X_train_full, y_train_full, X_test and y_test variables <br>
Normalize the data <br>
Create a validation set of 6000 images <br>
Create an ANN model with two dense layers of 200 and 100 neurons <br>
Compile and train the model for 60 epochs <br>
Plot the loss and accuracy against epoch <br>
Evaluate the model accuracy on the test dataset <br>
Predict the digit for the first 5 records of the test dataset <br>
