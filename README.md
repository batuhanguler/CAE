# CAE - Convolutional Autoencoder
Convolutional Autoencoder applied to CIFAR dataset

# Presentation
Autoencoders are neural networks used in unsupervised learning, in order to perform data compressing. The input is compressed in a latent-space representation and we try to reconstruct the input from this representation. 
Convolutional Neural Networks are very successful in image recognition. The shared parameters make the CNNs scale to high-dimensional problems and outperforms fully-connected neural networks.

Here, Convolutional Auto-encoders uses the scaling abilities of convolutional layers in order to perform dimensionnality reduction. 

# Performance Evaluation
The success of the CAE will be tested as follows:
 - **By the representation learning capabilities of your model**. In particular, autoencoders are known to be able to learn quite informative features in their latent space (embeddings) that can later be used for downstream tasks. We will  use the representations in order to do image classification.
 - **By the autoencoders' reconstruction error**. We will need to achieve a low enough error in order to reconstruct the images of the dataset with relatively high fidelity. We will look at the model's training loss curve, reconstruction error on the test set and some reconstructed images in the respective cells.
