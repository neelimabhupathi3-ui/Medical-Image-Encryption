## HYBRID CHAOTIC ENCRYPTION FOR SECURE MEDICAL IMAGE TRANSMISSION
# Abstract
 In the healthcare industry, medical image security is essential, particularly in telemedicine and cloud-based medical data storage, where there is a risk of data modification and unauthorized access.This project presents a hybrid chaotic image encryption technique designed to improve medical image security through an effective confusion-diffusion mechanism. It uses the Logistic-Henon Map for encryption key generation. The confusion phase involves random vector permutation, block rotation, and zigzag pattern transformation, while the diffusion phase uses XOR-based encryption to modify pixel intensities.The proposed technique is designed for both color and grayscale medical images. Its performance can be evaluated using metrics such as entropy, Number of Pixels Change Rate (NPCR), Unified Average Changing Intensity (UACI), and correlation coefficient analysis. The system aims to improve key sensitivity and provide secure medical image transmission in applications such as IoT and telemedicine.
 # Objectives
  - To provide security for medical images during transmission.
  - To generate encryption keys using chaotic maps.
  - To perform image encryption and decryption.
  - To prevent unauthorized access to medical images.
  - To provide a simple graphical user interface.
# Technologies Used
  - Python
  - OpenCV
  - NumPy
  - Tkinter
  - Pillow
# Methodology
  # Encryption Process
  - Upload the medical image.
  - Split the plain image into the required components.
  - Apply zigzag pattern transformation.
  - Rotate image blocks.
  - Perform random vector permutation.
  - Generate encryption keys using chaotic maps.
  - Apply diffusion to the scrambled image using the generated key.
  - Obtain the encrypted image.
 # Decryption Process
  - Apply reverse diffusion.
  - Reverse the confusion operations.
  - Reconstruct the original image.
  - Display the decrypted image.
# Features
 - Medical image uploading.
 - Chaotic-map-based key generation.
 - Image confusion and diffusion.
 - Image encryption and decryption.
 - Support for color and grayscale medical images.
 - Graphical user interface.
# Output
The application displays three images:
 - Original Image
 - Encrypted Image
 - Decrypted Image
# Installation
Install the required libraries:
  pip install -r requirements.txt
# How to Run
  medical_image_encryption.py
# Note
This project is an academic implementation for educational purposes. It is not intended for protecting actual patient records in production environments.
