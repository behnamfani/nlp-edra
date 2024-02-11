# Approach 1
A Variational Autoencoder (VAE) ([Kingma and Welling 2019](https://www.nowpublishers.com/article/Details/MAL-056)) is a generative model that combines autoencoder
concepts with probabilistic modeling. Its goal is to learn a hidden representation of input
data, capturing its underlying patterns in an unsupervised manner, enabling the generation of new, similar
samples, and providing a more meaningful representation. VAE structure consists of an Encoder,
Latent Space, and Decoder.
* Encoder: Input data is fed into an encoder neural network, which maps it to a distribution in the latent
space, reducing dimensionality and deriving mean and variance parameters for a (multivariate
Gaussian) distribution.
* Latent Space (Sampling): The ”reparameterization trick” combines the mean with the product of
standard deviation and random noise to create a latent vector, enabling random sample generation.
* Decoder: The decoder network reconstructs input data by mapping the latent vector back to the
original data space.
## Members
- Behnam Fanitabasi
- Mahnaz Mirhaj

## Description
<div style="display: flex; flex-direction: column; align-items: center;">
    <figure>
        <img src="/Approach%201/Encoder.png" alt="Encoder" width="400px" height="300px">
        <figcaption><b>Encoder</b></figcaption>
    </figure>
    <figure>
        <img src="/Approach%201/Decoder.png" alt="Decoder" width="300px" height="250px">
        <figcaption><b>Decoder</b></figcaption>
    </figure>
</div>

