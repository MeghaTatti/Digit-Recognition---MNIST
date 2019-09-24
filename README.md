# Digit-Recognition---MNIST
This project is built using the Keras implementation with tensorflow backend.

The MNIST (Modified National Institute of Standards and Technology) database is a large set of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning and computer vision. The black and white images from NIST were normalized to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.

Here, we are taking this as the primary input to our program of (CNN) conventional neural network (CNN). The following implementations are done to our network.

• Training it using the MNIST data set

• Differentiating between training set - A set of examples used for learning, that is to fit the parameters of the classifier and test set - A set of examples used only to access the performance of a fully specified classifier.

• Adding convolution 2D layers and pool layers with specified filter and kernel size.

• Computing cross entropy, changing the drop rate

• Optimizing using gradients to a specific learning rate

Run Using Google Colab

### Model Details:
1. Here we have used Sequential Convolution 2D model.
 
2. There are 2 layers with 32 and 64 filters of kernel size 5x5.

3. The datasets are MNIST dataset from “keras”.

4. 55000 samples are trained, and 10000 samples are tested for 5 epochs.

5. Pooling in both layers should downsample by factor 2 of 2.

6. Dropout rate is taken as 40%.
