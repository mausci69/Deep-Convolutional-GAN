# Deep-Convolutional-GAN

Deep Convolutional Generative Adversarial Network (DCGAN) is a very successful GAN model developed in 2015 (remember that GAN was a model developed in 2014). We use Conv2D and Conv2DTranspose modules, among the others. The Specialization I followed in Coursera uses PyTorch, but as a big fan of TensorFlow myself, I decided to follow the TensorFlow tutorial. It's still using the MNIST famous dataset, to see if we can generate handwritten digits similar to the ones present in the database. The training loop begins with the generator receiving a random seed as input. That seed is used to produce an image. The discriminator is then used to classify real images (drawn from the training set) and fakes images (produced by the generator). The loss is calculated for each of these models, and the gradients are used to update the generator and discriminator. GAN's training can be very slow so  I am training it for just 10 epochs.
