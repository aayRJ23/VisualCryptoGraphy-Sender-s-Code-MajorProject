# VisualCryptoGraphy-Sender's-Code-MajorProject (ONGOING)

## Introduction

This project demonstrates how to embed a secret message into an image using LSB (Least Significant Bit) steganography, then divide the image into four quadrants. The hidden message can only be extracted when all four quadrants are combined. This ensures the security of the secret message as it cannot be retrieved if any quadrant is missing.

To render the above code: visit the website [nbviewer](https://nbviewer.org/) and paste the link of this repository here to get rendered.

## Working of the Code

### 1. Upload and Display Image
- The user is prompted to upload an image.
- The uploaded image is read and converted to grayscale.
- The grayscale image is displayed.

### 2. Embed Secret Text
- The user is prompted to enter the secret message they want to hide.
- The secret message is converted into a binary format.
- Using the LSB steganography method, each bit of the binary text is embedded into the least significant bit of each pixel in the image.
- The image with the embedded secret message is displayed.

### 3. Divide Image into Quadrants
- The image is divided into four equal quadrants.
- Each quadrant is displayed.
- The quadrants are saved as separate image files.

## Requirements
- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- Google Colab (for file uploads)

## Usage
1. Clone the repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Run the notebook and follow the prompts to upload an image and enter a secret message.
4. The quadrants with the embedded message will be saved in the working directory.
