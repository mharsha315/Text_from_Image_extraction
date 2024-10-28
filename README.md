# Text_from_Image_extraction

## Description
This is a Flask-based web application that extracts text from images using OpenCV and Pytesseract. It allows users to upload an image, and the extracted text is displayed on the web interface.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Requirements](#requirements)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/mharsha315/Text_from_Image_extraction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Text_from_Image_extraction
    ```
3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the Flask application:
    ```bash
    python app.py
    ```
2. Open your browser and go to `http://localhost:5000` to access the application.
3. Upload an image and see the extracted text displayed on the page.

## Features
- Extracts text from uploaded images using Pytesseract.
- Supports various image formats like PNG, JPEG, etc.
- Built using OpenCV and Flask for image processing and web interfacing.

## Requirements
The project uses the following dependencies (found in `requirements.txt`):
- opencv-python-headless==4.2.0.32
- pytesseract==0.3.7
- numpy==1.19.3
- Flask==1.1.1
- Pillow==8.0.1
