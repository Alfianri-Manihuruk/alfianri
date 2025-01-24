---
title: "Detect Image Information Into Documents With OCR (Optical Character Recognition)"
description: "Smart OCR for Document Analysis"
dateString: Sep 2024
draft: false
tags: ["DL", "AI", "Python", "PyTorch", "OCR","Computer Vision"]
showToc: false
weight: 204
cover:
    image: "projects/ocr/cover.png"
--- 

## Link
- 🔗 [**Github**](https://github.com/Alfianri-Manihuruk/ImageToDocumentOCR)

## Summary

This project aims to enable computers to read text from images or scanned documents. OCR (Optical Character Recognition) serves as a bridge connecting the physical world (printed documents) with the digital world.

## Work Plan
- Environment Setup: Prepare the tools and conduct research related to OCR.
- Data Collection: Gather a dataset of images containing text.
- Data Preprocessing: Apply sharpening techniques and contrast adjustment to the images.
- OCR Implementation: Integrate OCR and develop text extraction functions.
- Column Segmentation: Add logic to divide the text by columns and test the results.
- Evaluation and Testing: Compare the OCR results with the original text and conduct iterative testing for improvements.

## Tools and Technologies
This OCR project leverages various tools and technologies to ensure high accuracy and efficiency in text extraction. 
Below are the main tools and libraries used:

- **Python**: The primary programming language used for development.
- **Tesseract OCR**: An open-source OCR engine that supports multiple languages and highly accurate text recognition.
- **OpenCV**: A powerful library for image processing and computer vision tasks.
- **PyTesseract**: A Python wrapper for Tesseract OCR, making it easy to use Tesseract's features within Python scripts.
- **Pandas**: A data manipulation and analysis library, used for handling and processing extracted text data.
- **NumPy**: A library for numerical computations in Python, used for various image processing tasks.
- **Flask**: A micro web framework for building the web-based user interface.
- **Jupyter Notebook**: An interactive environment for writing and running code, used for experimentation and visualization.


## Evaluation and Challenge
- Easy OCR 
1. Cannot detect special characters
2. OCR output format and structure are poor.
3. Requires low-end device.

- Tesseract
1. Special characters can be detected but poorly.
2. OCR output format and structure are poor.
3. Requires low-end device.

- Pre-trained model (GOT 2.0)
1. Can detect special characters well.
2. Format is fairly good, but only for certain documents (simple documents).
3. Requires high-end device.

The primary challenge in building and implementing OCR (Optical Character Recognition) lies in the often unstructured output. It is difficult to arrange OCR results to resemble the original document in a way that is easily understood by readers. Therefore, experience and in-depth knowledge are needed to achieve well-structured OCR output.

