# FCNN-in-Distributed-Systems

### Overview
This project explores the application of Fourier Convolutional Neural Networks (FCNNNs) for image classificaiton. FCNNs are designed to leverage the benefits of Fourier transforms in image processing, as proposed in recent academic literature (Pratt et al., 2017 & Ji et al., 2022). The project focueses on implementing and evaluating these models on two distinct datasets:
1. MNIST Dataset - A standard benchmark for handwritten digit classification.
2. UC Merced Land Use Dataset - A challenging dataset for land-use classification from aerial images.

### Repository Structure
The repository contains the following key components:
* FCNN.ipynb: Demonstrates the implementation and evaluation of the FCNN model on the MNIST dataset, capable of modifications to acquire various performance goals.
* FCNN_ucmerced.ipynb: Focuses on applying the FCNN modelto the UC Merced dataset, highlighting the challenges of generalizing Fourier-based approaches to more complex image data.
* README.md: This file, providing an overview of the project.

### Datasets
MNIST:
* The MNIST dataset consists of grayscale images of handwritten digits (0-9)

UC Merced:
* The UC Merced Land Use Dataset consists of 21 land-use classes, each with 100 images of 256x256 pixels.

### Results and Insights
* The MNIST notebook highlights the potential benefits and limitatinos of FCNNs on simpler datasets.
* The UC Merced notebook explores the challenges of extending FCNNs to more complex, high-resolution datasets and identifies areas for further optimization.

### Future Work
* Investigate architectural improvements to enhance FCNN performance on complex datasets.
* Experiment with hybrid approaches combining Fourier and spatial domain features.
* Explore data augmentation techniques to improve model generalization.

### Acknowledgements
This project builds on foundational work from recent papers on Fourier Convolutional Neural Networks. Special thanks to the acadmeic community for their contributions to this area of research, especially:
* Pratt et al. (2017)
* Ji et al. (2022)
* Dong et al. (2024)
