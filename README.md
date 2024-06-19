# AutoEncoders
This Repository will give explanations on different variations of AutoEncoders.

1. Dimensionality Reduction using AutoEncoders:
In the AutoEncoder-Dimensionality-Reduction.ipynb file, the crop dataset was taken and dimensionality reduction was performed on the x variables reducing the dataset from 7 to 2(the latent space representation). The KMeans Algorithm was further used to cluster the datapoints in the dataset to their respective classes.
link to the project: https://github.com/oluwafavourmi/AutoEncoders/tree/main/AutoEncoder%20Dimensionality%20Reduction

2. Convolutional AutoEncoders:
This Architecture uses Convolutional Layers and it is mainly used in Image analysis, since convolutional layers perform better than Dense layers. The architecture has an encoder-decoder structure and images are embedded into a latent space representation.
link to the project: https://github.com/oluwafavourmi/AutoEncoders/tree/main/Convolutional%20AutoEncoder

3. Variational AutoEncoders:
This particular variant of AutoEncoders was used as a Generative model and trained to generate new images from a Latent Space of 200 dimensions.