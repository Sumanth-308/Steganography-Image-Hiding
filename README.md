# 🔐 Steganography – Hiding Information in the Image 🖼️

This project demonstrates how to securely hide a secret message inside an image using XOR-based pixel manipulation with Python and OpenCV. It visually preserves the image while concealing the message, allowing for safe and undetectable communication.

---

## 🔧 Technologies Used
- 🐍 Python 3
- 📷 OpenCV (`cv2`) – Image reading & writing
- 🧮 NumPy – Numeric operations
- 📊 Matplotlib – Image display
- ☁️ Google Colab – Cloud-based coding environment

---

## 📁 Files Included
- `Steganography_Intern_Project.ipynb` – Main notebook with both encryption and decryption logic
- `stego_output.png` – Final output image with embedded secret message
- `images.jpeg` – Original input image used to embed the message
- `README.md` – This documentation file

---

## ✅ Output
- Secret message: `"secret"`
- Encrypted image: Visually identical to the original
- Message successfully extracted using the same XOR key

---

## 🔍 How It Works
1. Convert the message and key to ASCII.
2. Apply XOR operation between message and key characters.
3. Embed XOR result into the RGB pixel values of the image.
4. Save the result as a new image (`stego_output.png`).
5. For decryption, apply XOR again using the same key to retrieve the message.

---

## 📷 Screenshots (Included in PPT)
- 🔹 Encryption execution with image display  
- 🔹 Stego-image (`stego_output.png`)  
- 🔹 Decryption output showing the message `"secret"`

---

## 🎯 Goal
To implement and demonstrate a simple steganography method that hides data inside images using XOR logic, making the presence of the message undetectable.

---

## 🔗 GitHub Repository
This project is hosted at:  
👉 [https://github.com/Sumanth-308/Steganography-Image-Hiding](https://github.com/Sumanth-308/Steganography-Image-Hiding)

---

🛠️ Feel free to clone, use, or build upon this project for educational purposes!

