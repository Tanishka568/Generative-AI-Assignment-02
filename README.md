
# Comparative Study and Implementation of Generative AI Models

A comparative study of four generative AI models using the **Labeled Faces in the Wild (LFW)** face dataset.

## Models Implemented

1. **Autoencoder (AE)** – Learns compressed image representations and reconstructs input images.
2. **Variational Autoencoder (VAE)** – Learns probabilistic latent representations and generates new samples.
3. **Deep Convolutional GAN (DCGAN)** – Uses a generator and discriminator to generate realistic-looking face images.
4. **Diffusion Model** – Uses a pretrained diffusion model to generate images from text prompts.

## Project Overview

The objective of this project is to understand and compare different generative AI techniques based on their architecture, training behaviour, generated outputs, and performance.

The experiments use the LFW face dataset. The AE, VAE, and DCGAN are trained using the dataset, while the pretrained diffusion model is used for inference.

> **Note:** The diffusion model is pretrained and is not trained or fine-tuned on the LFW dataset in this project.

## Dataset Details

**Dataset:** Labeled Faces in the Wild (LFW)

- Image size: 64 × 64 pixels
- Image channels: RGB (3 channels)
- Dataset subset: Up to 3,000 images
- Training images: 2,700
- Validation images: 300

Dataset source: https://vis-www.cs.umass.edu/lfw/

The dataset is downloaded directly through the notebook. No Kaggle API token or manual dataset upload is required.


## Technologies Used

- Python
- TensorFlow / Keras
- PyTorch
- Hugging Face Diffusers
- NumPy
- Matplotlib
- Google Colab

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Generative-AI-Assignment-02.git
```

Move into the project folder:

```bash
cd Generative-AI-Assignment-02
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## How to Run

1. Open the notebook from the `notebooks/` folder.
2. Run it using Google Colab or Jupyter Notebook.
3. Select a GPU runtime if available.
4. Execute all cells in sequence.
5. Allow the dataset and pretrained model to download.
6. Observe the training outputs, generated images, and comparison results.

## Model Comparison

The project compares the four models based on:

- Model architecture
- Training process
- Reconstruction quality
- Image generation quality
- Loss behaviour
- Execution time, where measured
- Advantages and limitations

The results and observations are documented in the project report and notebook.

## Important Notes

- AE, VAE, and DCGAN are trained using the LFW dataset.
- The diffusion model uses pretrained weights for inference.
- Results may vary depending on hardware, random initialization, and training duration.
- Training time and diffusion inference time are different measurements.
- Evaluation metrics such as FID, SSIM, and PSNR should only be reported if they were actually calculated.

## Project Deliverables

- Complete Jupyter Notebook
- Project Report
- Generated Images
- Training Results and Comparisons

## References

- LFW Dataset: https://vis-www.cs.umass.edu/lfw/
- TensorFlow: https://www.tensorflow.org/
- PyTorch: https://pytorch.org/
- Hugging Face Diffusers: https://huggingface.co/docs/diffusers/

---

**Generative AI Assignment 02**  
Comparative Study and Implementation of Generative AI Models

