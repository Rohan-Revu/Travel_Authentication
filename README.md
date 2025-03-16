# 🚆 Face Recognition Travel Pass Verification System

This project is a **Face Recognition-based Travel Pass Verification System** using `DeepFace` and `OpenCV`.  
It verifies if a person's face matches a known database and checks if their **travel pass is valid**.

---

## 🚀 Features
✅ **Face recognition** using `DeepFace`  
✅ **Press 'c' to capture an image** from a webcam  
✅ **Matches the captured image** with stored images  
✅ **Checks travel pass validity** based on expiry date  
✅ **Displays passenger details** if a match is found  
✅ **Alerts if the pass has expired** or if no match is found  

---

## 📌 How It Works

### **1️⃣ Capture Image**
- Run the script in **Google Colab**.
- Press **'c'** to capture an image from the webcam.
- The image is saved as **`captured_image.jpg`**.

### **2️⃣ Face Recognition**
- The system compares the captured image with **stored known faces**.
- If a match is found:
  - ✅ Displays passenger details.
  - ✅ Checks **pass expiration date**.

### **3️⃣ Eligibility Check**
- **If the pass is valid** ➝ 🟢 **Eligible to Travel**  
- **If the pass is expired** ➝ 🔴 **Not Eligible to Travel**  
- **If no match is found** ➝ ❌ **Not Recognized**  

---

## 📜 Code Overview

### **Capture Image**
The script allows users to capture an image by pressing `'c'`:
