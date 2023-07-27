# Image Steganography - Hide Data in Images 🖼️🔍

![Steganography](https://img.shields.io/badge/Steganography-Python-brightgreen)

This project showcases a Python application for image steganography, allowing users to hide textual data within an image using the `tkinter` and `PIL` (Python Imaging Library) libraries. The steganographic technique used in this application hides the data within the least significant bits of the image's RGB pixels, making it imperceptible to the human eye.

## Features:

- **Encode Data:** Embed text data inside an image using the least significant bits of the image's RGB pixels.
- **Decode Data:** Extract hidden data from an image that was encoded with steganography.

## Usage:

1. **Installation:**

   Ensure you have the following Python libraries installed:

   - `tkinter`: Included in most Python installations.
   - `Pillow`: Install using `pip install Pillow`.

2. **Run the Application:**

   Execute the `steganography.py` script.

3. **Encoding:**

   - Click the "Encode" button to initiate the encoding process.
   - Select an image in which you want to hide the text data.
   - Enter the message in the text area.
   - Click the "Encode" button to hide the data within the image.
   - The encoded image will be saved as "Image_with_hiddentext.png" in the same directory.

4. **Decoding:**

   - Click the "Decode" button to initiate the decoding process.
   - Select an image with hidden text data.
   - The hidden data will be displayed in the text area.

## Important Notes:

- Make sure to select an appropriate image for encoding, as images with too much compression might result in a noticeable distortion.
- The application currently supports image formats such as PNG, JPEG, and JPG.

## Example:

Here's an example of how the steganography application works:

1. ![Original Image](example/original_image.jpg)

2. ![Encoded Image](example/encoded_image.jpg)

3. ![Decoded Text](example/decoded_text.png)

The original image is on the left, the image with encoded text is in the middle, and the decoded text is on the right.

**Note**: The decoded text is "Hello, this is a hidden message!".

Feel free to use this steganography tool for secure data embedding within images! 🔒📜🖼️
