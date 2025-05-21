                                            

# 🩸 Blood Group Detection From Fingerprint 🩸

## 📌 Introduction  
Blood group detection using fingerprints combines biometric identification with machine learning to determine a person's blood group from their fingerprint image.  
This method is **non-invasive, quick, and beneficial** in medical emergencies where a patient’s blood group is not readily available.

---

## 🎯 Objective  
To develop a **machine learning model** that can predict a person's blood group based on fingerprint image analysis, and integrate it with a **user-friendly web application**.

---

## 🛠️ Prerequisites and Installation

### 🔧 Software & Libraries Required:
- Python 3.8 or higher  
- pip (Python package installer)

### 📚 Libraries:
- `opencv-python`  
- `numpy`  
- `pandas`  
- `scikit-learn`  
- `matplotlib`  
- `flask` (for web app)  
- `tensorflow` or `pytorch` (for deep learning models)

### 🧪 Installation Steps:
```bash
pip install opencv-python numpy pandas scikit-learn flask matplotlib



```

---

## 🔬 Methodology

### 📥 Data Collection:
- Gather a dataset of **fingerprint images** with known blood group labels (A, B, AB, O).
- Ensure consistent **resolution and format** for images.

### 🧹 Preprocessing:
- Convert images to **grayscale**.
- Apply **Gaussian blur** for noise reduction.
- Enhance features using **Sobel/Canny edge detection**.

### 📈 Feature Extraction:
- Use **Gabor filters**, **Local Binary Patterns (LBP)**, or **deep CNN features**.
- Extract **texture, ridge orientation, and minutiae points**.

### 🧠 Model Training:
- Split dataset into **training** and **testing** sets.
- Apply classifiers such as:
  - Random Forest
  - Support Vector Machine (SVM)
  - Convolutional Neural Network (CNN)
- Evaluate with **cross-validation**.

### 🧪 Model Testing:
- Validate using **unseen fingerprint images**.
- Use metrics like **Accuracy**, **Precision**, **Recall**, **F1 Score**.

### 🌐 Integration with Flask Web App:
- Create a form with:
  - Name  
  - Mobile  
  - Gender  
  - Age  
  - Fingerprint Upload  
- Process the image on submission and **predict blood group**.
- Display results in a **summary table**.

### 📤 Output Display:
The output includes:
- Name  
- Mobile  
- Gender  
- Age  
- Predicted Blood Group  

---

## 💻 User Interface Design

The frontend is built with **HTML/CSS** and connected to the backend via **Flask**.

### Key Features:
- 🎨 Responsive and clean UI
- 📋 Form with:
  - Name
  - Mobile Number
  - Gender (Dropdown)
  - Age (Dropdown or Input)
  - Fingerprint File Upload
- 🖼️ Preview of uploaded fingerprint
- 🔘 Button to trigger detection and display result

---

## 🎥 Output

![Screenshot (156)](https://github.com/user-attachments/assets/17c531c7-ec77-4cee-8b4f-11a0aeacb3ef)


![Screenshot (157)](https://github.com/user-attachments/assets/e2812060-b69b-4b4b-a265-f4311335e5a0)



Upon successful form submission and fingerprint processing:

✅ User details are displayed in a **result table**  
✅ The **predicted blood group** is shown clearly

### 📹 [Output Demo Video](https://drive.google.com/file/d/1TSO5Nl0i-pCpYdHEggQ2fCqSRkQKBqKd/view?usp=drive_link)

---

## ✅ Conclusion

This project showcases an innovative approach to **blood group detection using biometric data**.  
While traditional blood testing remains more accurate, this system serves as a **promising supplementary tool** in healthcare and emergency scenarios.

---










