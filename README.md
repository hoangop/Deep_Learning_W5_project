# Deep Learning Week 5: Monet Style Generation with GANs

This project aims to generate images in the unique style of Claude Monet using Generative Adversarial Networks (GANs).

## Problem Description

The goal is to build a GAN consisting of a Generator and a Discriminator to transform standard photos into Monet-style paintings. 
- **Generator:** Creates Monet-style images from input photos.
- **Discriminator:** Distinguishes between real Monet paintings and generated images.
- **Metric:** The performance is evaluated using **MiFID** (Memorization-informed Fréchet Inception Distance).

## Dataset

The dataset includes:
- **Monet Paintings:** ~300 images (Training data for style).
- **Photos:** ~7000 images (Source data to be transformed).

Data formats provided include JPEG and TFRecord.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hoangop/Deep_Learning_W5_project.git
   cd Deep_Learning_W5_project
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

   *Note: The project uses TensorFlow 2.16.2 and Keras 3.12.0.*

## Usage

The main project logic is contained in the Jupyter Notebook:
- `notebook/project-w5.ipynb`

You can run this notebook using Jupyter Lab or Jupyter Notebook:

```bash
jupyter lab notebook/project-w5.ipynb
```

## Project Structure

```
.
├── notebook/
│   ├── project-w5.ipynb    # Main project notebook
│   └── project.ipynb       # Previous version/Reference
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

## Acknowledgments

- University of Colorado Boulder - Deep Learning Course
- Kaggle "I'm Something of a Painter Myself" competition dataset

