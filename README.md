# SecurStego
SecureStego is a web-based image steganography and steganalysis framework that securely hides encrypted messages inside PNG images using multiple embedding techniques. It combines AES-256-GCM encryption, digital watermarking, steganalysis, image quality metrics, and role-based user/admin dashboards into a single platform.
# 🔐 SecureStego

**SecureStego** is a web-based image steganography, encryption, digital watermarking, and steganalysis framework developed as a Cyber Security project. It allows users to conceal confidential messages inside PNG images using multiple steganographic embedding techniques, with encryption providing an additional layer of security.

The platform combines secure message embedding and extraction with image analysis tools to demonstrate both the practical applications and limitations of digital steganography.

### ✨ Key Features
- **Encrypted Steganography:** Protect hidden messages using AES-256-GCM encryption and password-based key derivation.
- **Multiple Embedding Techniques:** Supports seven image-based message embedding methods.
- **Message Extraction:** Retrieve hidden messages from stego images with password-based decryption.
- **Digital Watermarking:** Add, verify, and trace visible and invisible digital watermarks.
- **Steganalysis Laboratory:** Analyze stego images and evaluate their detectability.
- **Image Quality Analysis:** Evaluate image distortion using metrics such as PSNR, MSE, and other performance measurements.
- **Experiment & Benchmark Tools:** Compare embedding methods based on capacity, image quality, and execution time.
- **User & Admin Dashboards:** Role-based access control with separate user and administrator workspaces.
- **Web-Based Interface:** Interactive web application designed for practical demonstrations and cybersecurity learning.

### 🛠️ Technologies Used
Python, Flask, Cryptography, HTML, CSS, JavaScript, Image Processing, AES-256-GCM, PBKDF2.

SecureStego is designed as an educational and experimental framework for exploring image steganography, cryptography, digital watermarking, and steganalysis.
