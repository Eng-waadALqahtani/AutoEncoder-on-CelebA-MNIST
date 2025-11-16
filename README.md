🌟 AutoEncoder Project – CelebA & MNIST Embedding Analysis

This repository contains two full deep-learning experiments using Convolutional AutoEncoders (Conv-AE) implemented in PyTorch.
The goal is to explore reconstruction quality, latent representations, and the effect of different embedding sizes across two datasets.

📂 Repository Structure
AutoEncoder_Project/
│
├── CelebA/
│     ├── CelebA_AutoEncoder_Report.pdf
│     ├── celeba_autoencoder.ipynb
│     ├── results/
│     └── gifs/
│
└── MNIST/
      ├── MNIST_AutoEncoder_Report.pdf
      ├── mnist_autoencoder.ipynb
      ├── results/
      └── gifs/

🧠 1) CelebA AutoEncoder

AutoEncoder trained on the CelebA face dataset to learn compact embeddings and reconstruct facial images.
Two embedding sizes were explored: 32 and 64 dimensions.

Key Features

Dataset: CelebA

Model: Convolutional AutoEncoder (PyTorch)

Embedding sizes: 32, 64

Outputs include:

Training loss

Reconstruction samples

Latent space projections (PCA & t-SNE)

Embedding histograms

Latent-dimension interpolation

✏️ 2) MNIST AutoEncoder

AutoEncoder trained on MNIST handwritten digits dataset to investigate the effect of very small latent dimensions.

Embedding sizes tested

2

5

10

20

Outputs include

Training loss curves

Reconstructed digits

PCA & t-SNE comparisons

Latent distributions

Interpolation GIFs

🛠️ Technologies Used

PyTorch

NumPy

Matplotlib

PCA & t-SNE

Convolutional AutoEncoder

CelebA & MNIST datasets

👩‍💻 Author

Waad Alqahtani
AI & Deep Learning • Saudi Arabia
