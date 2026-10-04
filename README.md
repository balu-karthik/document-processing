# Document Processing

This repository contains notebooks for exploring document image processing, OCR, and preprocessing techniques using Python.

## Contents

- `document-processing.ipynb` — end-to-end document processing workflow with OCR and image preprocessing
- `intro_to_pytesseract.ipynb` — introduction to Tesseract OCR and basic text extraction
- `opencv.ipynb` — OpenCV-based image processing and enhancement examples

## Project focus

The notebooks in this repository demonstrate how to:

- read and preprocess scanned or photographed documents
- clean and enhance images for OCR
- extract text using Tesseract
- use OpenCV for denoising, thresholding, and image transformations
- work with document images in a notebook-based workflow

## Typical workflow

1. Load an image or scanned document
2. Apply preprocessing steps such as grayscale conversion, resizing, thresholding, and denoising
3. Improve OCR accuracy using OpenCV techniques
4. Extract text with `pytesseract`
5. Review and refine results for downstream use

## Requirements

These notebooks are designed for Python environments such as:

- Jupyter Notebook
- Google Colab
- local Python environments with notebook support

Common dependencies include:

- Python 3
- OpenCV
- Pillow
- pytesseract
- Tesseract OCR engine

## Setup

Install the required packages:

```bash
pip install opencv-python pillow pytesseract
```

Make sure the Tesseract binary is installed on your system:

- Ubuntu/Debian: `sudo apt-get install tesseract-ocr`
- macOS: `brew install tesseract`
- Windows: install from the official Tesseract release and add it to PATH

## Notes

These notebooks are intended for experimentation and learning in document OCR and image processing. They can be adapted for invoice processing, scanned document cleanup, form extraction, and similar OCR workflows.
