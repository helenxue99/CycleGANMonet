# CycleGANMonet

This Kaggle competition to practice building and training generative deep learning models (mostly GAN). Kaggle introduces an evaluation metric called MiFID (Memorization-informed Fréchet Inception Distance) score to evaluate the quality of generated images.

DCGAN (Deep Convolutional Generative Adversarial Network) is a type of neural network architecture that is commonly used for generating images. It typically consists of two parts: a generator network that generates new images, and a discriminator network that tries to distinguish between real and generated images. CycleGAN (Cycle-Consistent Adversarial Networks) is a type of generative adversarial network (GAN) used for image-to-image translation.

The basic idea behind CycleGAN is to learn a mapping between two different image domains, such as converting images from a summer scene to a winter scene or from a horse to a zebra. This is done by training two deep neural networks simultaneously: a generator network that creates images in the target domain from input images in the source domain, and a discriminator network that tries to distinguish between real images in the target domain and generated images.

CycleGAN is unique in that it uses a cycle-consistency loss term that helps to ensure that the mapping between the two domains is consistent in both directions. This means that if you start with an image in the source domain, convert it to the target domain, and then convert it back to the source domain, you should end up with an image that is similar to the original. This helps to prevent artifacts and inconsistencies in the generated images.


The code includes the following parts:
1. Load Library
2. Loading Image data
3. Preprocessing the image data
4. Create Model
  4.1 Create Generator
  4.2 Create discriminator
  4.3 Create Cycle Gan Model
5. Training Model
6. Generate sample Monet Image
7. Generate submission zip file for images
Output Model
