# FashionGAN: Generative Adversarial Network for Fashion Images (TNSDC-GEN-AI)

This project implements a Generative Adversarial Network (GAN) using TensorFlow for generating fashion images based on the Fashion MNIST dataset. The GAN consists of a generator and a discriminator trained in an adversarial setup to produce realistic fashion images.

## Project Structure

- `FashionGAN.ipynb`: Jupyter Notebook containing the code for training and testing the GAN.

- `images/`: Directory to save generated images during training.

- `generator.h5`: Saved model file for the generator.

## Dependencies

Ensure the following dependencies are installed:

- tensorflow
- matplotlib
- tensorflow-datasets
- ipywidgets

You can install the dependencies using pip:

```bash
pip install tensorflow matplotlib tensorflow-datasets ipywidgets
```

## Usage

1. Run `notebook.ipynb` to train the GAN and generate fashion images.
2. Monitor training progress using the loss plots.
3. View generated images in the `images/` directory.
4. Use the saved generator model (`generator.h5`) for generating new fashion images.

## Additional Notes

- This project uses TensorFlow and TensorFlow Datasets for data loading and model training.
- The GAN consists of a generator and discriminator trained in an adversarial setup.
- The `ModelMonitor` callback saves generated images at the end of each training epoch.
