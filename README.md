# Text Recognition with PyTesseract - Computer Vision Project

This repository contains a computer vision project that performs text recognition using PyTesseract. The project leverages Optical Character Recognition (OCR) techniques to extract text from images, enabling easy digitization of printed text from various sources.

## Project Overview

This project uses PyTesseract, an open-source OCR tool, to recognize and extract text from images. The goal is to facilitate text recognition in images, making it useful for applications such as document digitization, image-to-text conversion, and retrieving information from visual content. The project also explores methods to improve OCR accuracy through image preprocessing techniques like thresholding, noise removal, and contrast adjustment.

## Features

- **Image Preprocessing**: Includes functions to enhance image quality before text recognition, improving OCR accuracy.
- **Text Extraction**: Uses PyTesseract to extract text from images and displays it as editable text.
- **Flexible Applications**: Adaptable for real-time OCR applications, scanned document processing, and more.

## Requirements

- **Python 3.6+**
- **PyTesseract**
- **OpenCV**
- **Pillow (PIL)**

To install the required dependencies, run:
```bash
pip install pytesseract opencv-python pillow
