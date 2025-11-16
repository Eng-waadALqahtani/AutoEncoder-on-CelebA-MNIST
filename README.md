AutoEncoder Project — CelebA & MNIST Embedding Analysis

This repository contains two complete AutoEncoder experiments using PyTorch:

CelebA AutoEncoder → Face dataset

MNIST AutoEncoder → Handwritten digits

Both experiments focus on latent space behavior, reconstruction quality, and embedding visualization using PCA, t-SNE, histograms, and latent-dimension interpolation GIFs.

📁 Repository Structure
AutoEncoder_Project/
│
├── CelebA/
│     ├── CelebA_AutoEncoder_Report.pdf
│     ├── celeba_autoencoder.ipynb
│     ├── results/ (reconstructions, PCA, t-SNE, histograms)
│     └── gifs/ (latent dimension interpolation)
│
└── MNIST/
      ├── MNIST_AutoEncoder_Report.pdf
      ├── mnist_autoencoder.ipynb
      ├── results/ (reconstructions, PCA, t-SNE, histograms)
      └── gifs/ (latent dimension interpolation)

🎨 CelebA AutoEncoder

Input: 64×64 RGB faces

Embedding Sizes Tested: 32, 64

Outputs included:

Reconstruction results

PCA & t-SNE latent visualizations

Embedding histograms

Latent dimension interpolation GIFs

Full report: CelebA_AutoEncoder_Report.pdf

✏️ MNIST AutoEncoder

Input: 28×28 grayscale digits

Embedding Sizes Tested: 2, 5, 10, 20

Outputs included:

Reconstruction images

PCA & t-SNE comparisons

Latent space scatter plots

Embedding histograms

GIF interpolation (size = 2)

Full report: MNIST_AutoEncoder_Report.pdf

⚙️ Technologies Used

PyTorch

NumPy

Matplotlib

PCA & t-SNE

Conv AutoEncoder architecture

CelebA & MNIST datasets

👤 Author

Waad Alqahtani
