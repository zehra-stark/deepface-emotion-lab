🎓 Project Title: DeepFace Emotion Detection Lab

📝 Overview:
A beginner-friendly AI project that uses DeepFace and Amazon SageMaker to detect emotions and gender from facial images captured via webcam. The system captures a photo locally, uploads it to Amazon S3, and analyzes it within a cloud-hosted Jupyter notebook — all using lightweight, cost-efficient tools suitable for AWS Free Tier.

🧰 Tech Stack Used (and Why):
- **Python**: Core programming language for scripting, data handling, and integration.
- **OpenCV (headless)**: Lightweight computer vision backend for image capture and processing without GUI, ideal for server environments like SageMaker.
- **DeepFace**: High-level facial analysis library used to detect emotion, gender, and optionally age.
- **Amazon S3**: Simple storage service to store and retrieve captured webcam images.
- **Amazon SageMaker**: Managed Jupyter notebook environment to run DeepFace inference without needing local compute power.

✨ Features:
- Capture webcam images via terminal Python script
- Upload images directly to Amazon S3
- Use SageMaker Jupyter Notebook to analyze facial emotion and gender
- Efficient use of CPU resources by choosing `opencv` as the backend
- Screenshots and outputs saved for visual documentation

🚀 Future Enhancements:
- Add age and race detection with optimized memory handling
- Auto-trigger notebook processing upon S3 upload (via AWS Lambda)
- Frontend integration for real-time emotion detection
- Dockerize and deploy as a microservice using AWS Lambda or Fargate

📸 Screenshots:

| Emotion    | Screenshot               |
|------------|--------------------------|
| 😊 Happy    | ![](screenshots/01.png) |
| 😠 Angry    | ![](screenshots/02.png) |
| 😱 Fear     | ![](screenshots/03.png) |
| 😲 Surprise | ![](screenshots/04.png) |

🖼️ Sample Output:


```text
Predicted Emotion: happy
Predicted Gender: Man


🐞 Problems Faced:
- DeepFace crashes on low-memory SageMaker instances when age detection is included
- Kernel auto-restarts due to memory overflow from heavy models
- GitHub push failures due to divergence and rebase conflicts
- Face detection fails on low-light or blurred images

🎓 What I Learnt:
- Integration of Python scripts with AWS services (S3 & SageMaker)
- Use of DeepFace for real-world facial analysis
- Working with Git and resolving push/rebase conflicts
- Optimizing resources on SageMaker for smooth notebook execution

🌟 What Makes This Project Unique:
- Fully cloud-based facial analysis system built by an individual from scratch
- Combines AWS, Computer Vision, and Machine Learning in a single workflow
- Efficiently designed to work within AWS Free Tier limits
- Simplified enough for anyone to replicate, yet powerful for real-world testing

👩‍💻 Developed By:
**Nivetha Velmurugan**

📁 Repository:
[deepface-emotion-lab](https://github.com/zehra-stark/deepface-emotion-lab)

📌 Tools Used:
- Python, OpenCV, DeepFace
- Amazon S3, SageMaker
- GitHub for version control

🔚 One Final Note:
**"Even a simple face can teach you deep tech — when cloud, code, and curiosity come together."**

