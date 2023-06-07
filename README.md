# Repository Info

This repository contains work done for my Deep Learning Module Assignment 2 at SP
The scope of the assignment consisted of training Generative Adversarial Networks to generate images from the CIFAR10 dataset

You can go to https://wandb.ai/bevanpoh/cifar10_gan view the training history for all of the model runs in this project


- `cifar_gan.ipynb` contains the code for the whole modelling process documented with markdown comments
- `cifar_gan.html` is simply the notebook exported to `.html` format

- `models` contains training code for the different models
    - `dcgan` contains code for standard DCGAN with strong_disc, strong_gen and balanced
    - `laplacian` contains code for models trained on processed data using pre-trained weights, fresh weights
    - `infogan` contains code for infoGANS with one categorical, with 2 FC head q network, with one semi-supervised categorical

- `processed` contains low quality images singled out using the variance of laplacian
    - `messy` contains images with high variance
    - `unfocussed` contains images with low varaince

- `upsample` contains weights for final 1000 image evaluation
