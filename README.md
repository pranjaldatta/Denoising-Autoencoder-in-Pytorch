# DenoisingAutoencoderPytorch
A Pytorch Implementation of a denoising autoencoder.

# Denoising Autoencoder
An autoencoder is a neural network used for dimensionality reduction; that is, for feature selection and extraction. Autoencoders with more hidden layers than inputs run the risk of learning the identity function – where the output simply equals the input – thereby becoming useless.

Denoising autoencoders are an extension of the basic autoencoder, and represent a stochastic version of it. Denoising autoencoders attempt to address identity-function risk by randomly corrupting input (i.e. introducing noise) that the autoencoder must then reconstruct, or denoise.




# The Implementation
1) Two kinds of noise were introduced to the standard MNIST dataset: Gaussian and speckle, to help generalization.
2) The autoencoder architecture consists of two parts: encoder and decoder. Each part consists of 3 Linear layers with ReLU activations. The last activation layer is Sigmoid.
3) The training was done for 120 epochs.
4) Visualizations have been included in the notebook.
5) Used Google's Colaboratory with GPU enabled.

