# 🎬 MultiMedia Course Projects - Fall 2021

[![Made With](https://img.shields.io/badge/Made%20with-Python-blue)]()
[![University](https://img.shields.io/badge/University-IUT-orange)]()

---

## 📚 Table of Contents

- [About The Repository](#about-the-repository)
- [Homeworks](#homeworks)
  - [HW01 - Image Manipulation & MSE Calculation](#hw01---image-manipulation--mse-calculation)
  - [HW02 - Histogram and Local Processing](#hw02---histogram-and-local-processing)
  - [HW03 - Quantization & DCT Compression](#hw03---quantization--dct-compression)
  - [HW04 - Shadow and Hybrid Images](#hw04---shadow-and-hybrid-images)
  - [HW05 - Color Region Modification](#hw05---color-region-modification)
- [How to Use](#how-to-use)

---

## 📖 About The Repository

This repository contains my coursework for the **MultiMedia** class at **Isfahan University of Technology (Fall 2021)**.

It includes five homework assignments implemented in **Python**, covering various multimedia processing techniques.

---

## 📝 Homeworks

### HW01 - Image Manipulation & MSE Calculation
- Perform various image transformations:
  - Horizontal flip
  - Transpose
  - Cropping
  - Shifting (right, left, up, down, diagonal)
- Calculate **Mean Squared Error (MSE)** between original and modified images.
- Resize images using **nearest**, **bilinear**, and **bicubic** interpolation methods.
- Analyze the effect of shifts and resizing on image quality.

### HW02 - Histogram and Local Processing
- Plot **histogram** and **cumulative distribution function (CDF)** of images.
- Implement **global histogram equalization**.
- Implement **local histogram equalization** by dividing the image into blocks.
- Perform **watermark embedding** into images using bit-level manipulation and measure image distortion with **MSE**.

### HW03 - Quantization & DCT Compression
- Implement **histogram median cut** for segmenting image brightness levels.
- Apply **uniform quantization** to compress images.
- Perform **Discrete Cosine Transform (DCT)**:
  - Zero out low-magnitude DCT coefficients.
  - Reconstruct the image using **Inverse DCT**.
  - Calculate **PSNR** and visualize the sparsity (percentage of zeroed coefficients).

### HW04 - Shadow and Hybrid Images
- Add **shadow effect** to an image by combining the original image and a **Gaussian-blurred** version.
- Create **hybrid images** by blending:
  - Low-frequency content from one image.
  - High-frequency content from another.
- Observe different perceptions when viewed from near and far.

### HW05 - Color Region Modification
- Allow user to **click** on an image to select a target color.
- Find and modify all pixels within a defined **color tolerance** (`w`) of the selected color.
- Replace selected pixels with a **new color** specified by the user.

---

## 🚀 How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ARSH2001/MultiMedia.git
2. Navigate to the desired homework folder:
   ```bash
     cd MultiMedia/HW01
3. Run the Python scripts:
   ```bash
     python script_name.py
