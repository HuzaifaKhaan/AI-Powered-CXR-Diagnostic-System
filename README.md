# AI-Powered CXR Diagnostic System

![work1](https://github.com/user-attachments/assets/dca04480-a4cd-4966-b2d4-dacad3b36eed)

## Overview

Welcome to the AI-Powered CXR Diagnostic System! This project utilizes advanced AI and machine learning techniques to streamline the radiologist workflow by automating the analysis of chest X-ray (CXR) images. Built with PyTorch and Flask, this system uses a DenseNet121 pretrained model from `torchxrayvision` to detect 14 different pathologies with high accuracy, making the diagnostic process faster and more efficient.

## Features

- **Accurate Detection**: Leverages the DenseNet121 model from `torchxrayvision` for precise identification of 14 different pathologies in CXR images.
- **User-Friendly Interface**: Simple and intuitive web interface for uploading and analyzing images.
- **Real-Time Results**: Provides quick diagnostic results to assist radiologists in making informed decisions.

## Technologies Used

<div>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" height="40" alt="Python">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" width="40" height="40" alt="PyTorch">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" width="40" height="40" alt="Flask">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="40" height="40" alt="Docker">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" width="40" height="40" alt="GitHub">
</div>

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/HuzaifaKhaan/AI-Powered-CXR-Diagnostic-System.git
    cd AI-Powered-CXR-Diagnostic-System
    ```

2. **Create a Virtual Environment and Activate It**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Flask Application**:
    ```bash
    python app.py
    ```

2. **Open Your Browser and Navigate to**:
    ```
    http://127.0.0.1:5000
    ```

3. **Upload a CXR Image**:
    - Click on the "Upload" button and select a CXR image from your local machine.

4. **Get Diagnostic Results**:
    - The system will analyze the image using the DenseNet121 model and display the diagnostic results on the screen.

## Project Structure

```plaintext
.
├── app.py                # Main application file
├── requirements.txt      # Project dependencies
├── static/               # Static files (CSS, JS, images)
├── templates/            # HTML templates
├── testing_images/       # Directory for test images
└── .vscode/              # VSCode configuration files
