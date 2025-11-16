
# 🌟 Convolutional Autoencoders for Image Manifold Learning (MNIST & CelebA)
<img width="1024" height="1024" alt="Gemini_Generated_Image_qbrn3iqbrn3iqbrn" src="https://github.com/user-attachments/assets/b352057a-675c-4978-90f0-47be6612d7f9" />

This project explores the performance and latent space representations of **Convolutional Autoencoders (CAE)** by applying them to two distinct image datasets: the simple **MNIST** handwritten digits and the complex **CelebA** celebrity faces dataset.

The primary goal is to understand how the CAE model compresses images into a lower-dimensional latent space and how the quality of reconstruction and the structure of the latent space change with varying embedding sizes.

---

## 🚀 Key Features and Results

* **PyTorch Implementation:** Deep learning models (CAEs) implemented entirely in PyTorch for both encoder and decoder architectures.
* **Multi-Dimensional Latent Space Analysis:** Models were trained and evaluated across various latent vector sizes to study the trade-offs:
    * **MNIST:** Latent dimensions **2, 5, 10, 20**.
    * **CelebA:** Latent dimensions **32, 64**.
* **Latent Space Visualization:** The learned embeddings are visualized using both **Principal Component Analysis (PCA)** and **t-distributed Stochastic Neighbor Embedding (t-SNE)** to demonstrate the clustering and structure within the compressed space.
* **Latent Interpolation (GIFs):** Code is included to generate GIF animations showing the smooth image transitions (interpolation) achieved by manipulating individual dimensions of the latent vector.
* **Performance Metrics:** Detailed analysis of **Training Loss** curves and visualization of **Reconstructed Images** for each embedding size.

---

## 📂 Project Structure

| File Name | Description |
| :--- | :--- |
| `MINST_Conv_AutoEncoder_Pytorch.ipynb` | Jupyter Notebook for implementing, training, and testing the CAE on the **MNIST** dataset. Includes visualization code for reconstructed images and latent space. |
| `waad _MNIST_AutoEncoder_Report.pdf` | Detailed analysis report on the MNIST autoencoder, covering loss plots, PCA/t-SNE visualizations, and reconstruction quality for embedding sizes **2, 5, 10, and 20**. |
| `waad_Conv_AutoEncoder_Pytorch_CelebA.ipynb` | Jupyter Notebook for implementing, training, and testing the CAE on the **CelebA** dataset (requires downloading/accessing the dataset). |
| `waad_AutoEncoder on CelebA.pdf` | Detailed analysis report on the CelebA autoencoder, including loss curves, latent space projections (PCA/t-SNE), and reconstructed face images for embedding sizes **32 and 64**. |

---

## 🛠️ Prerequisites and Installation

To run the notebooks and reproduce the results, you will need the following libraries installed:

* Python (3.x recommended)
* `torch`
* `torchvision` (for dataset loading and transformations)
* `numpy`
* `matplotlib`
* `scikit-learn` (for PCA and t-SNE)
* `imageio` (for generating GIF animations)

You can install the primary dependencies using pip:

```bash
pip install torch torchvision numpy matplotlib scikit-learn imageio
````

-----

## 🏃‍♂️ How to Run the Code

1.  **Clone the Repository:**
    ```bash
    git clone <Your Repository URL>
    cd <repository-name>
    ```
2.  **Launch Jupyter:**
    ```bash
    jupyter notebook
    ```
3.  **Run the Notebooks:**
      * For **MNIST** analysis: Open and execute the cells in `MINST_Conv_AutoEncoder_Pytorch.ipynb`. The MNIST dataset will be downloaded automatically by `torchvision`.
      * For **CelebA** analysis: Open and execute the cells in `waad_Conv_AutoEncoder_Pytorch_CelebA.ipynb`. *Note: You may need to manually download or configure access to the CelebA dataset.*
4.  **Review Reports:** The PDF reports (`.pdf` files) contain the summarized findings, visualizations, and conclusions from the experiments.

-----

## 📊 Key Insights from Analysis

### MNIST (Simple Data Manifold)

  * The latent space visualization (t-SNE) for the **2-dimensional** embedding size shows remarkable separation and distinct clustering of different digit classes (0-9), indicating the autoencoder effectively learned the core distinguishing features.
  * Increasing the latent size to 10 or 20 significantly reduces the reconstruction loss, resulting in nearly perfect image fidelity, but the 2D space is the most interpretable for visualization.

### CelebA (Complex Data Manifold)

  * Due to the high dimensionality and complexity of face data, higher latent dimensions (**32 and 64**) were required.
  * The training loss curves demonstrate consistent convergence, achieving high-quality facial reconstruction.
  * Latent space interpolation GIFs show successful semantic transitions between face images, demonstrating that the autoencoder has captured meaningful features of the face manifold (e.g., changes in hair, expression, or background).

-----

## 🖋️ Author

**WAAD ALQAHTANI** 

```
```
