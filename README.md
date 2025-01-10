# Generative Adversarial Networks (GAN) Project

This project focuses on building, training, and testing a Generative Adversarial Network (GAN) using PyTorch. The goal is to generate high-quality, visually convincing images while addressing common GAN training challenges.

## Project Overview
The project leverages GANs for image generation tasks, utilizing datasets such as CelebA and AnimeFace. Key objectives include designing a Deep Convolutional GAN (DCGAN) architecture, stabilizing GAN training, and exploring transfer learning techniques.

## Key Features
- **Model Implementation**:
  - Designed and implemented a DCGAN architecture in PyTorch.
  - Trained models to generate realistic images from latent vectors.
  
- **Transfer Learning**:
  - Fine-tuned pre-trained GAN models to adapt to domain-specific tasks, such as generating AnimeFace images.

- **Training Stability**:
  - Addressed challenges in GAN training, including balancing generator and discriminator convergence.
  - Experimented with hyperparameters to achieve stable and effective training.

## Datasets
- **CelebA Dataset**: A large-scale face attributes dataset used for generating realistic human faces.
- **AnimeFace Dataset**: A domain-specific dataset for generating high-quality anime-style images.

## Results
- Generated visually appealing and realistic images for both datasets.
- Demonstrated the effectiveness of DCGAN in handling complex data distributions.
- Explored the potential of transfer learning in improving GAN performance.

## Tools and Technologies
- **PyTorch**: For building and training the GAN models.
- **Matplotlib**: For visualizing training progress and generated images.
- **Google Colab**: Used as the development environment for its GPU support.
