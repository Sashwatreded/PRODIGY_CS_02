# 🖼️ Image Encryption & Decryption using Pixel Manipulation (Python GUI)

This project is an **Image Encryption and Decryption tool** built using Python, NumPy, and Tkinter.  
Developed as part of my internship at **Prodigy Infotech**, the tool allows users to encrypt and decrypt images using simple pixel value manipulation with a key-based method.

The interface is built with **Tkinter**, offering a smooth and interactive user experience.

---

## 🔐 How It Works

- Each pixel in the image is composed of Red, Green, and Blue (RGB) values.
- The encryption process **modifies pixel values** using a key (simple addition).
- Decryption is done by **reversing** the process using the same key (subtraction).
- Uses `NumPy` arrays for efficient pixel manipulation.

---

## 🚀 Features

- Load and display original images
- Encrypt images using a numeric key
- Decrypt back to the original using the same key
- Save the encrypted image
- GUI-based operation for ease of use

---

## 🛠️ Tech Stack

- Python
- `NumPy` for array manipulation
- `Pillow (PIL)` for image handling
- `Tkinter` for GUI design

---

## 📋 Functional Steps

1. **Open Image**  
   Select an image file using a file dialog.

2. **Encrypt Image**  
   Shift each pixel's RGB value by a key using NumPy operations.

3. **Decrypt Image**  
   Subtract the key to recover the original image.

4. **Save Image**  
   Save the encrypted or decrypted image as a file.

5. **Display Images**  
   View original, encrypted, or decrypted versions side-by-side.

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-encryption-tool.git
   cd image-encryption-tool
