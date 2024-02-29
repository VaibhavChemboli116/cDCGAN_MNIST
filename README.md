# cDCGAN_MNIST
# Handwritten Digit Generation using Conditional DCGANs

Creating accurate images of handwritten numbers has been a challenging task. The introduction of Generative Adversarial Networks (GAN) has shown promising results in generating realistic images by randomly selecting from the latent space. However, GAN outputs can be unpredictable and challenging to regulate. To address this, Conditional GANs (cGAN) have been introduced, allowing additional information (such as labels) to guide the image generation process, which inturn allowing the generation of customized images of specific numbers.

### cDCGAN Architecture

The project employs a conditional deep convolutional GAN (cDCGAN) to train the MNIST dataset along with labels. cDCGAN incorporates deep convolutional layers to extract more features, enabling the restoration of features more prominently compared to other GAN architectures like Fully Connected GAN, WGAN, etc.

## MNIST Dataset

The [MNIST dataset](http://yann.lecun.com/exdb/mnist/) is a well-known collection of 70,000 small images of handwritten digits (0-9), each measuring 28x28 pixels. The entire dataset is used to train the cDCGAN model in this project.

## Project Findings

The findings demonstrate that GANs, particularly cDCGANs, can be an effective approach for generating realistic images of handwritten digits. Conditional training allows for the regulation of output, providing flexibility in customizing generated images based on specific labels.

Feel free to explore the code and contribute to this project. If you have suggestions or improvements, please open an issue or submit a pull request.

Happy generating! 🖋️
