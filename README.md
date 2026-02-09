

# 🧑‍🤖 Age and Gender Detection using OpenCV & Deep Learning

## 🚀 Project Overview
This AI-powered project detects faces and predicts **age** & **gender** from images or video streams using OpenCV and deep learning. 🧠💡

🔹 **Face Detection** 👀  
🔹 **Gender Classification** 🏷️ (Male/Female)  
🔹 **Age Estimation** 📊 (from predefined age groups)  
🔹 **Live Video & Image Support** 🎥🖼️

---

## 🛠️ Tech Stack & Dependencies
- **Python** 🐍
- **OpenCV** 🎭
- **Pre-trained Deep Learning Models** 🏗️
- **NumPy** 🔢
- **Argparse** 🏗️

### 📌 Install Dependencies
```bash
pip install opencv-python numpy argparse
```

---

## 📥 Pre-trained Models Used 
This project leverages state-of-the-art **deep learning models** for accurate predictions:

📌 **Face Detection:** `opencv_face_detector.pbtxt` & `opencv_face_detector_uint8.pb`
📌 **Age Prediction:** `age_deploy.prototxt` & `age_net.caffemodel`
📌 **Gender Classification:** `gender_deploy.prototxt` & `gender_net.caffemodel`

Ensure these files are in your working directory. 📂✅

---

## 🎯 How to Use

### 🖼️ Run with an Image
```bash
python age_gender_detection.py --image path/to/image.jpg
```

### 🎥 Run with Live Webcam
```bash
python age_gender_detection.py
```

---

## ⚙️ How It Works
1️⃣ **Detect Faces** using OpenCV's deep learning module.  
2️⃣ **Pre-process Images** for the model.  
3️⃣ **Predict Gender & Age** using trained models.  
4️⃣ **Overlay Results** on the image/video feed.  

---

## 📌 Example Output
📝 The detected **age** and **gender** are displayed in the console and overlaid on the image.

---

## 📜 License
This project is open-source and available under the **MIT License**ok

---

## ✨ Author
👤 Modassir Ali
💼 My LinkedIn - https://www.linkedin.com/in/codehub01/

Enjoy building with AI! 🚀🤖

