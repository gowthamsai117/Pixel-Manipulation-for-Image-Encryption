# Pixel-Manipulation-for-Image-Encryption

## Image Encryption Tool

This is a simple image encryption tool that encrypts and decrypts images using basic pixel manipulation techniques. The tool swaps pixel values and applies basic mathematical operations to each pixel to obscure the original image. This is not intended for high-security encryption but rather for educational purposes and simple use cases.

## Features

- **Encrypt Image**: Encrypt an image by manipulating its pixels.
- **Decrypt Image**: Decrypt an encrypted image back to its original form.

## Requirements

- Python 3.x
- PIL (Pillow)

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/image-encryption-tool.git
    cd image-encryption-tool
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Encrypt an Image**:
    ```bash
    python encrypt.py --input input_image.png --output encrypted_image.png
    ```

2. **Decrypt an Image**:
    ```bash
    python decrypt.py --input encrypted_image.png --output decrypted_image.png
    ```

## Example

To encrypt an image:

```bash
python encrypt.py --input example.png --output example_encrypted.png
