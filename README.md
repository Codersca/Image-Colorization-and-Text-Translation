
# Image Colorization, Text Extraction & Translation

This project demonstrates an end-to-end pipeline that performs the following tasks:

1. **Colorizes grayscale images** using a custom convolutional neural network built with PyTorch.
2. **Extracts text** from the colorized image using Keras-OCR.
3. **Translates** the extracted text into Hindi using the `translate` Python library.

---

## 🚀 Features

- Image colorization using a 4-layer CNN with dilated convolutions
- Image classification on CIFAR-10 dataset (used for training)
- Real image colorization from grayscale input
- Optical Character Recognition (OCR) with Keras-OCR
- Language translation (English to Hindi)

---

## 🛠️ Installation

Before running the code, install the required libraries:

```bash
pip install torch torchvision keras-ocr translate matplotlib
