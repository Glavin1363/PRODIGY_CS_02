Overview:

This project is a simple image encryption tool developed using pixel manipulation techniques. The tool allows users to encrypt and decrypt images by performing basic operations on pixel values. The encryption and decryption processes ensure that the image data is transformed in a way that is reversible, allowing the original image to be restored.

Features
Image Encryption: Encrypts an image by altering its pixel values through various operations.
Image Decryption: Reverses the encryption process to restore the original image.
User-Friendly Interface: Simple and intuitive interface for users to select images, encrypt, and decrypt them.
How It Works
Pixel Manipulation Techniques
The tool uses basic pixel manipulation techniques to encrypt and decrypt images. Here are two example techniques:

Swapping Pixel Values:

This method involves swapping the values of pixels based on a predefined pattern or algorithm.
For example, swap the values of adjacent pixels or pixels at specific intervals.
Mathematical Operations:

Apply a basic mathematical operation to each pixel value.
For example, add or subtract a fixed number to/from each pixel value, or use a more complex operation like bitwise XOR with a key.
Encryption Process
Load Image: The user loads an image into the tool.
Encrypt Pixels: The tool processes each pixel in the image according to the chosen encryption method (e.g., swapping pixels, applying mathematical operations).
Save Encrypted Image: The encrypted image is saved and can be viewed as a scrambled or altered version of the original.
Decryption Process
Load Encrypted Image: The user loads the encrypted image into the tool.
Decrypt Pixels: The tool processes each pixel in the encrypted image by reversing the encryption method.
Save Decrypted Image: The decrypted image, which should match the original image, is saved.
Usage
Clone the Repository: Clone this GitHub repository to your local machine.
Install Dependencies: Ensure you have the necessary libraries installed (e.g., PIL or OpenCV for image processing in Python).
Run the Tool: Execute the script to launch the image encryption tool.
Encrypt an Image:
Load an image using the provided interface.
Choose the encryption method.
Encrypt the image and save the output.
Decrypt an Image:
Load the encrypted image.
Decrypt the image using the same method and parameters used for encryption.
Save the decrypted image, which should match the original.
