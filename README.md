# PRODIGY_PME_02

PRODIGY_PME_02
🔐 Pixel Manipulation for Encryption
Prodigy Infotech Internship — Task 2

This project demonstrates how to perform basic image encryption and decryption using pixel-wise manipulation (XOR operation) with a randomly generated key.

📌 Project Objective
To apply image processing and cryptographic techniques by manipulating pixel values to securely encrypt and decrypt images.

🧠 How It Works
The image is read using the Pillow library and converted into a NumPy array.
A random key (array of integers) is generated and resized to match the image's dimensions.
The image is encrypted using a bitwise XOR operation with the key.
The same XOR operation with the same key is used again to decrypt the image back to its original form.
📂 File Structure
├── image_encryption.py # Main Python script ├── encrypted_image.png # Output encrypted image (generated) ├── decrypted_image.png # Output decrypted image (generated) └── README.md # Project documentation

markdown Copy Edit
