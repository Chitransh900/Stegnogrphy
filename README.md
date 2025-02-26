# Stegnogrphy
Problem Statement (Precise Version)
With increasing digital communication, securing sensitive information is a major challenge. Traditional encryption methods make hidden data obvious, whereas steganography conceals information within images, making it nearly undetectable. This project aims to securely embed and extract secret messages inside images using pixel manipulation while ensuring authentication via a passcode.

# Technology Used
Programming Language: Python
Libraries: OpenCV (cv2), OS, String
Platform: Windows

# Wow Factors (Unique Features)
Uses image pixels for hiding text, making detection difficult.
Passcode-protected encryption & decryption adds a security layer.
Lightweight and fast processing due to direct pixel modification.
Works with any standard image format (JPEG, PNG, etc.).

# End Users
Cybersecurity professionals (for secure communication)
Journalists & Whistleblowers (to hide sensitive data)
Individuals concerned about privacy
Educational purposes (learning cryptographic techniques)

# Results (Expected Output)
The input message is successfully hidden inside the image.
The encrypted image is generated and can be opened like a normal image.
Upon entering the correct passcode, the hidden message is retrieved.
If an incorrect passcode is entered, access is denied.

# Conclusion
This project effectively demonstrates image-based steganography as a secure way to hide sensitive messages within images. Unlike encryption, which makes data visibly protected, this method ensures covert communication by embedding text in image pixels. The added passcode authentication enhances security, making it a practical tool for privacy-conscious users.
