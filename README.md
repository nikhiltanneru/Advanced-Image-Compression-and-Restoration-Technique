# Advanced-Image-Compression-and-Restoration-Techniques

This repository contains the project files and codebase for the exploration of Advanced Image Compression and Restoration Techniques. The project focuses on enhancing compression efficiency and restoring high-quality images using both traditional methods and state-of-the-art deep learning approaches.

## Overview
#### Objectives
- To study and compare traditional, modern, and deep learning-based image compression methods.
- To implement restoration methods using GANs and Autoencoders.
- To evaluate performance on the DIV2K dataset with metrics like PSNR, SSIM, and LPIPS.

#### Challenges
- Balancing compression efficiency, image quality, and computational complexity.
- Handling hardware and dataset limitations.

#### Proposed Solution
A model combining state-of-the-art compression formats (e.g., AVIF, WebP) with deep learning-based restoration techniques to improve image quality.

## Repository Structure
#### 📁 Data Preperation/
##### Data_Preparation.ipynb
- Jupyter notebook to download and prepare the DIV2K dataset from Kaggle.
- Output: Training, validation, and test datasets with both high-resolution and degraded low-resolution images.

#### 📁 Image Compression/

##### Image_Compression_Final.ipynb
- Implements and compares 5 image compression algorithms (3 traditional: JPEG, PNG, JPEG2000; and 2 modern: AVIF, WebP). Evaluates results using metrics like PSNR, SSIM, compression ratio, and decoding time.

#### 📁 Image Restoration/


##### DnCNN/
-  "DnCNN.ipynb:" Implements a Deep Convolutional Neural Network for image denoising and evaluates using PSNR, SSIM, and MSE.

##### ESR_GAN/
- "ESR_GAN_Implementation_DIP.ipynb:" Implements Enhanced Super-Resolution GAN to upscale and restore degraded images.
- "Metrics_for_ESR_GAN_DIP.ipynb:" Evaluates ESRGAN using PSNR, SSIM, and LPIPS.

##### SwinIR/
- "Swin_IR.ipynb:" Uses SwinIR (Swin Transformer for Image Restoration) with medium and large models for super-resolution tasks.

##### U_Net/
- "U_Net.ipynb:" Implements U-Net for image restoration, focusing on improving PSNR and SSIM.

## How To Use

#### Setup Environment:

- Use Google Colab or a local environment with GPU support.
- Install dependencies as instructed in the notebooks.

#### Run Data Preparation:

- Open Data_Preparation.ipynb in Colab.
- Follow the steps to download the DIV2K dataset from Kaggle to your Google Drive.


#### Image Compression:

- Open Image_Compression_Final.ipynb.
- Test different compression algorithms on a sample image and evaluate the results using PSNR, SSIM, compression ratio, and decoding time.


#### Image Restoration:

- Choose any model folder (DnCNN, ESR_GAN, SwinIR, U_Net).
- Run the corresponding .ipynb file to perform restoration tasks.
- Evaluate performance using metrics provided in the notebooks.


## Key Features
#### Compression Methods:

- Traditional: JPEG, PNG, JPEG2000.
- Modern: AVIF, WebP.

#### Restoration Models:

- GANs for super-resolution and restoration.
- Autoencoders for dimensionality reduction and feature extraction.

#### Evaluation Metrics:

- Compression Ratio
- PSNR (Peak Signal-to-Noise Ratio)
- SSIM (Structural Similarity Index)
- LPIPS (Learned Perceptual Image Patch Similarity)

#### Dataset:
- DIV2K: High-resolution dataset with diverse scenes and textures.


## Powerpoint Presentation File:
#### [GROUP_11_PPT.pptx](https://github.com/user-attachments/files/17903264/GROUP_11_PPT.pptx)


## Limitations
- Computational complexity of deep learning models.
- Dependence on high-quality datasets.
- Generalization challenges in real-world scenarios.
