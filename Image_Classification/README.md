# Variational Autoencoder (VAE) for MNIST Dataset

This repository contains a Python implementation of a Variational Autoencoder (VAE) to generate hand-written digit images from the MNIST dataset. VAE is a type of generative model that can learn to encode high-dimensional data into a lower-dimensional latent space and then decode it back to the original data distribution.

## Requirements

To run the code in this repository, you will need the following packages:

- Keras
- Numpy
- Matplotlib
- Scipy

You can install these packages using pip:

```bash
pip install keras numpy matplotlib scipy

## Usage

1. Clone the repository:

git clone <repository_url>
cd vae-mnist

2. Run the VAE model:

The VAE model is implemented in the vae.py script. You can run it with the following command:

python vae.py

The script will train the VAE on the MNIST dataset for 10 epochs and generate a grid of 15x15 hand-written digit images. The resulting images will be saved in the results/vae directory.

# Details of the VAE Model

The VAE model consists of an encoder network and a decoder network.

## Encoder Network

The encoder network takes the input images of shape (28, 28, 1) and processes them through several convolutional and dense layers. The output of the encoder is a pair of vectors representing the mean (`z_mean`) and the log variance (`z_log_var`) of the latent space.

## Latent Space Sampling

The `sampling` function takes the mean and log variance from the encoder output and generates samples from the latent space using the reparameterization trick.

## Decoder Network

The decoder network takes the sampled latent vectors and decodes them back into images. It consists of dense and transpose convolutional layers to generate the final image.

## Custom Variational Layer

The `CustomVariationalLayer` is a custom Keras layer used to calculate the VAE loss, which is a combination of the binary cross-entropy loss and the Kullback-Leibler (KL) divergence loss. This layer ensures that the model is trained to reconstruct the input images while simultaneously learning a meaningful latent representation.

## Results

The trained VAE will generate a 15x15 grid of hand-written digit images. The grid will be saved in the `results/vae` directory with the filename "grid.png".

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the MIT License.

## Acknowledgments

The implementation of the VAE is based on the work of researchers in the field of deep learning and generative models. We acknowledge the contributions of the Keras, TensorFlow, and other open-source libraries that make this work possible.
