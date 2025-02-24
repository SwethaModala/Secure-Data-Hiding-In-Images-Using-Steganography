# Image Steganography in Python

## Description
This project demonstrates basic **steganography**, a method of hiding secret messages inside an image by modifying pixel values. The program allows users to encrypt a message into an image and later decrypt it using a passcode.

## Technologies Used
- **Python** (Programming Language)
- **OpenCV (`cv2`)** (Image Processing)
- **ASCII Encoding** (Character Mapping)
- **Basic Steganography** (Hiding Data in Images)
- **OS Module** (File Handling)

## Features
- Encrypt a secret message into an image.
- Secure the message with a passcode.
- Extract and decrypt the message using the correct passcode.

## Installation
1. Install Python (if not already installed):
   ```sh
   https://www.python.org/downloads/
   ```
2. Install required dependencies:
   ```sh
   pip install opencv-python
   ```
3. Place the image (`mypic.png`) in the same directory as the script.

## Usage
1. Run the script:
   ```sh
   python steganography.py
   ```
2. Enter a secret message and a passcode for encryption.
3. The script will create `encryptedImage.jpg` with the hidden message.
4. To decrypt, re-run the script and enter the correct passcode.

## Example
### Encryption:
```
Enter secret message: Hello World
Enter a passcode: 1234
```
### Decryption:
```
Enter passcode for Decryption: 1234
Decryption message: Hello World
```

## Limitations
- The message length must not exceed the number of available pixels.
- Basic security; an advanced cryptographic approach would be more secure.

## Future Improvements
- Use **LSB (Least Significant Bit) Steganography** for better security.
- Support multiple image formats.
- Implement a GUI for ease of use.

## Author
[Your Name]

