# CNN-Image-Classification

This project demonstrates image classification using a Convolutional Neural Network (CNN) on the CIFAR-10 dataset. The code begins by loading the dataset, which consists of 10 classes of images (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck). The images are preprocessed by normalizing their pixel values to a range between 0 and 1.

The CNN model is built using the Keras Sequential API. It comprises three convolutional layers, each followed by a max pooling layer to reduce spatial dimensions. The final layers flatten the output of the convolutional layers and use dense layers to classify the images into 10 categories. The model is compiled using the Adam optimizer and the Sparse Categorical Crossentropy loss function. It is trained for 15 epochs with the training set and validated on the test set.

**Libraries:**
* **TensorFlow:** The core library for building and training the CNN model. 
* **Keras:** A high-level API for building and training neural networks on top of TensorFlow.
* **Matplotlib:** Used for visualizing the images and displaying the training progress.

**Technologies:**
* **Convolutional Neural Networks (CNNs):** The architecture used for image classification, featuring convolutional layers for feature extraction and pooling layers for dimensionality reduction.
* **CIFAR-10 Dataset:** A widely used benchmark dataset for image classification, containing 60,000 color images labeled into 10 classes.
* **Adam Optimizer:** An efficient optimization algorithm commonly used for training deep neural networks.
* **Sparse Categorical Crossentropy:** A loss function suitable for multi-class classification problems, where each example belongs to only one class.
