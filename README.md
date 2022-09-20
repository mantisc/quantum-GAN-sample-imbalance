This task aims to solve the common sample imbalance with a hybrid quantum-classical GAN model. A classical
generator learns and generates fake data that are in similar distribution of real data, and a quantum discriminator
determines whether the input data is real or fake. If a classifier which is trained on the augmented dataset with
synthesized data can recognize different classes impartially, then quantum GAN functions.

The model is applied in an Insurance Claims dataset that contains less than 1% of positive samples.

![image](https://github.com/mantisc/quantum-GAN-sample-imbalance/blob/main/qGAN_output.jpg)
