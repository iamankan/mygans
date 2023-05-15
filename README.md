# About
This is a repository is for basic implementation of GAN, inspired from DCGAN and follows the documentation from [here](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html).


## Notations
- Let $x$ be an image. $D(x)$ is the discriminator that outputs scalar probability that $x$ came from training data rather than the generator. For images, $D(x)$ input is an image with size $(3 \times 64 \times 64)$. So, the $D(x)$ should be HIGH when data cpomes from training data and LOW when the $x$ comes from generator. So, $D(x)$ is basically a binary classifier.
- Now, coming to the generator. Let $z$ be a latent space vector sampled from a normal distribution. $G(z)$ represents the generator function, which maps the latent vector $z$ to data-space. (![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) ?? I don't understand this.)
