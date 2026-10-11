# GAN Generation and Latent Space Exploration

Image generation and latent-space experiments in PyTorch. A convolutional GAN learns to generate MNIST digits, while a pretrained CelebA generator supports experiments with face interpolation and vector arithmetic.

## Features

- MNIST GAN with a 50-dimensional latent space, trained for 50 epochs.
- Training-loss curves and generated-image grids.
- Linear interpolation between latent vectors for digits and faces.
- Latent subtraction, three-vector combinations, and averaging.

## Usage

```bash
pip install torch torchvision numpy matplotlib
```

Open [`gan_latent_space.ipynb`](gan_latent_space.ipynb) to view the saved results or run the cells in order. MNIST downloads automatically.

For the CelebA experiments, place the compatible `dcgan.py` wrapper and pretrained `generator.pt` checkpoint beside the notebook.
