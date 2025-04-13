Overview

The facial verification system utilizes deep learning techniques to compare facial features and determine the similarity between two images. It employs a Siamese Neural Network architecture, which is a popular choice for one-shot learning tasks like face verification.

The Siamese Neural Network consists of two identical subnetworks, often called "twins," which share the same weights and architecture. The twin networks process each input image separately and produce embeddings, which are vector representations of the input images in a high-dimensional feature space. The embeddings are then compared to calculate the similarity between the images.

Requirements

Python 3.x
TensorFlow
Keras
OpenCV
Kivy
