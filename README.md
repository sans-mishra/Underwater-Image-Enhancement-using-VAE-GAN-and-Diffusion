# Underwater-Image-Enhancement-using-VAE-GAN-and-Diffusion
The repository contains a project for underwater image enhancement using three models: Variational Autoencoder (VAE), Generative Adversarial Network (GAN) and Diffusion Model. The special underwater environment makes the photo take poor contrast, color distortion and haziness mainly in outdoor images. This project is about enhancing the visibility of images under water using state-of-the-art deep learning models.

# Features

* Three deep learning models are used for underwater image enhancement:

* VAE for unsupervised representation learning.
   * Conditional GAN with a U-Net Generator and PatchGAN discriminator
   * Iterative noise removal and detail restoration using Diffusion Model

* Evaluation to extract the metrics of processed images:

   * Peak Signal-to-Noise Ratio (PSNR)
   * Structural Similarity Index (SSIM)
   * MSE (Mean Squared Error)
   These metrics provide a comprehensive understanding of how well each model enhances underwater images.
* Performance comparison of individual models
# Dataset
The dataset used for training the models consists of underwater images collected from various sources, which capture common underwater artifacts such as haze, color casts, and noise. It consists of raw and enhanced images for both training and testing.
# Future Work
* Implementing additional image enhancement techniques.
* Experimenting with different datasets and augmentations.
* Optimizing training time and memory usage.
* Fine-tuning hyperparameters for each model for better results.  
