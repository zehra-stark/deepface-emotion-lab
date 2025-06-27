# 🎓 DeepFace Emotion Detection Lab

This project is a beginner-friendly emotion and gender detection system using DeepFace, OpenCV, and Amazon SageMaker.

## 📌 Features
- Captures image from webcam and uploads to S3
- Detects Emotion and Gender using DeepFace
- Uses lightweight `opencv` backend to reduce CPU load on SageMaker

## 🧰 Tech Stack
- Python
- DeepFace
- OpenCV
- Amazon SageMaker
- Amazon S3

## 🚀 How to Run
1. Run `upload_image_to_s3.py` to capture and upload image to S3.
2. Use Jupyter Notebook in SageMaker to analyze the image using DeepFace.

## 🔐 Prerequisites
- AWS CLI configured with proper permissions
- S3 bucket created
- SageMaker notebook instance running

## 🖼️ Sample Output

```text
Predicted Emotion: happy
Predicted Gender: Man
