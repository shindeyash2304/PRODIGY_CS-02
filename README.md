# PRODIGY_CS-02
Pixel Manipulation Image Encryption 
This project implements a basic image encryption and decryption tool using pixel manipulation techniques. The tool allows users to securely encrypt images and later decrypt them using a secret key.
Features:

Encryption: Applies a mathematical operation (XOR) to each pixel of the input image using a user-provided key.
Decryption: Reverses the encryption process to recover the original image.
User Interface: Simple command-line interface for easy interaction.

Implementation Details:

Language: Python
Libraries: Pillow (PIL) for image processing, NumPy for efficient array operations
Encryption Method: XOR operation between image pixels and a repeating key

How It Works:

The user provides an input image path, output image path, and a numeric key.
The program reads the image and converts it to a NumPy array.
The key is expanded to match the size of the image data.
An XOR operation is performed between the image data and the expanded key.
The resulting data is saved as a new image (encrypted or decrypted).

Usage:
CopyEnter 'e' to encrypt, 'd' to decrypt, or 'q' to quit: e
Enter the path to the input image: /path/to/input/image.jpg
Enter the path for the output image: /path/to/output/encrypted_image.jpg
Enter the encryption/decryption key (a string of numbers): 123 45 67 89
Image encrypted successfully!
