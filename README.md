The MNIST data is a database of handwritten digits from 0 to 9. The database contains 60,000 28x28 grayscale images of the 10 digits, along with a test set of 10,000 images. The task is to create a CNN model for identifying the digit from the handwritten images. 

The following tasks are performed: 

Load the database to variable named digit_mnist using the Keras inbuilt datasets (digit_mnist = keras.datasets.mnist) <br> 
Import data to create X_train_full, y_train_full, X_test and y_test variables <br>
Reshape the independent (X) data <br>
Normalize the data <br>
Create a validation set of 6000 images <br>
Create a CNN model (Model_A) with a Conv layer of filters = 32, kernel_size = (3, 3), strides=1, padding='valid', a Max pooling layer of 2 by 2 window and two dense layers with 200 and 100 neurons <br>
Compile and train the model for 60 epochs <br>
Plot the loss and accuracy against epoch <br>
Evaluate the model accuracy on the test dataset <br>
Create another model (model_B) with number of filter =64 <br>
Compare the performance and execution time for Model_A and Model_B <br>
