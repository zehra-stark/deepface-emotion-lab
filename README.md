# 🎓 DeepFace Emotion Detection Lab

A beginner-friendly AI project that detects **emotion** and **gender** from webcam images using `DeepFace`, `OpenCV`, and `Amazon SageMaker`. The entire pipeline is cloud-based and ideal for AWS Free Tier users.

---

## ✨ What This Project Does

- 📷 Captures image from webcam via terminal script  
- ☁️ Uploads the image to **Amazon S3**  
- 🧠 Analyzes image in **SageMaker Jupyter Notebook** using DeepFace  
- 🚹 Detects Emotion & Gender (with lightweight OpenCV backend)  
- 🪶 Uses minimal resources – perfect for students & beginners

---

## 🧰 Tech Stack

- 🐍 **Python** – glue that holds it all together  
- 🧠 **DeepFace** – handles emotion/gender detection  
- 🖼️ **OpenCV (headless)** – captures and processes images efficiently  
- 📦 **Amazon S3** – stores webcam images in the cloud  
- 🔬 **Amazon SageMaker** – runs Jupyter Notebooks without local setup  
- 🗂️ **GitHub** – version control and collaboration  

---

## 🚀 How to Use

1. ✅ Capture an image using `upload_image_to_s3.py`  
2. ✅ Confirm it uploads to your **S3 bucket**  
3. ✅ Launch a SageMaker Jupyter Notebook  
4. ✅ Run DeepFace on the uploaded image  
5. ✅ Get results like emotion and gender instantly!

---

## 🖼️ Emotion Samples

📸 **Captured Output Samples from the Model**

- 😊 **Happy**
  ![](screenshots/01.png)

- 😠 **Angry**
  ![](screenshots/02.png)

- 😱 **Fear**
  ![](screenshots/03.png)

- 😲 **Surprise**
  ![](screenshots/04.png)

---

## 🐞 Problems Faced

- 💥 Kernel restarts on low-memory SageMaker when using age/race detection  
- ❌ GitHub push conflicts (solved via rebase and manual conflict resolution)  
- 😵‍💫 Face not detected in low light or blurry captures  
- 🧠 DeepFace overload if `opencv` backend not chosen carefully  

---

## 🌟 Why This Project is Unique

- 🧩 Integrates **cloud computing**, **AI**, and **DevOps** in one flow  
- 🔁 Designed to work completely within AWS Free Tier  
- 🧪 Can be reused for other face-based use cases (e.g., ID verification)  
- 🪄 Clean, lightweight, and fast — built entirely from scratch

---

## 🧠 What I Learned

- Seamless integration of Python with AWS services  
- Handling real-world AI model memory issues  
- Using Git like a pro: commits, rebase, push conflicts  
- Visualizing outputs clearly using screenshots and notebooks

---

## 📌 Repository

🔗 Project done by ZEHRA STARK!
**[View Project on GitHub →](https://github.com/zehra-stark/deepface-emotion-lab)**

---

## 💡 Future Enhancements

- ➕ Add `age` and `race` detection using optimized flow  
- ⚙️ Trigger analysis automatically on S3 upload via Lambda  
- 🌐 Build a frontend UI for live webcam interaction  
- 📦 Package as a Docker app for microservice deployment

---

> _“Power isn’t determined by your size, but by the size of your dream and how far you’re willing to go to protect it.”_

---
