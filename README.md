# steganography-project-Bushra
# 🖼️ Hiding a Text Inside Image Using Steganography

## 🔐 Project Overview
This project demonstrates how to hide a secret text message inside an image using the **Least Significant Bit (LSB)** steganography technique with Python.  
It was developed as part of the **Edunet Foundation Cybersecurity Internship**.

---

## 👩‍💻 Developed By
**Bushra Shaikh** 

---

## 🧠 Objective
- To create a beginner-friendly Python tool that hides text messages inside images.
- To use the LSB technique to embed binary data without changing the visible image.
- To decode and retrieve the hidden message accurately.

---

## 🛠️ Technologies & Libraries Used
- Python 3  
- Jupyter Notebook  
- PIL (Pillow)  
- NumPy  

---

## 🚀 Features
- Embed any secret text message inside an image (.png format)
- Extract hidden message from an encoded image
- Output image looks visually identical to the original
- Optional: Generate pixel difference image to visualize LSB changes

---

## 📁 Folder Structure
├── steganography.py / encode_decode.py 
├── steganography_notebook.ipynb 
├── image for hide text.png # Original image
├── output.png # Encoded image
├── Steganography_Project_BushraShaikh.pptx # Project PPT
└── README.md

---

## 📌 How to Run
1. Clone the repository
2. Install required libraries:
   ```bash
   pip install pillow numpy

Run the encode_message() function with your message

Use decode_message() to extract it back

📚 **References**
Python Official Docs – https://docs.python.org/3/

Pillow (PIL) – https://pillow.readthedocs.io/

NumPy – https://numpy.org/

Edunet Foundation Internship Resources

**💡 Future Scope**
Add encryption (e.g., AES) to the message

Build GUI using Tkinter or a web interface

Extend to image-in-image steganography
https://github.com/Bushrashaikh07/steganography-project-Bushra.git
