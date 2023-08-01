# create-monet-gan
Monet Style Art Creation Using GAN

The objective of this project is to develop a generative adversarial network (GAN) which will convert regular photos into Monet style paintings. A GAN is made up of at least two neural networks, i.e. a generator model and a discriminator model. As this is an adversarial model, the generator and the discriminator will work in opposition to eventually create more realistic images.

In this project, I will employ the use of CycleGAN. According to the tensorflow website, CycleGAN is able to train without the use of paired data, as the GAN employs an additional cycle consistency loss function. This proves to be beneficial, as CycleGAN can translate between two domains without having a one-to-one mapping between them. Because of this, CycleGAN is able to do tasks such as style transfer, which is the main objective of this project.
