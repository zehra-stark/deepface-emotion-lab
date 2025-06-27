project:
  title: DeepFace Emotion Detection Lab
  description: >
    A beginner-friendly AI project that detects emotion and gender from webcam images
    using DeepFace and Amazon SageMaker. Lightweight, fully cloud-integrated, and optimized
    for AWS Free Tier.

  author: Nivetha Velmurugan
  repo: https://github.com/zehra-stark/deepface-emotion-lab

  tech_stack:
    - Python
    - OpenCV (headless)
    - DeepFace
    - Amazon S3
    - Amazon SageMaker
    - GitHub

  features:
    - Capture webcam images via terminal
    - Upload to Amazon S3 directly
    - Analyze with DeepFace inside SageMaker Jupyter Notebook
    - Lightweight `opencv` backend to reduce CPU usage
    - Screenshot outputs saved for documentation

  screenshots:
    - emotion: Happy
      file: screenshots/01.png
    - emotion: Angry
      file: screenshots/02.png
    - emotion: Fear
      file: screenshots/03.png
    - emotion: Surprise
      file: screenshots/04.png

  sample_output:
    emotion: happy
    gender: Man

  problems_faced:
    - Kernel crashes when age detection enabled on low-memory SageMaker instances
    - DeepFace model causes kernel restarts due to high memory
    - Git push failures due to rebase and divergence issues
    - Detection fails in low-light or blurry webcam images

  key_learnings:
    - Integrated AWS S3 & SageMaker using Python
    - Used DeepFace for practical facial analysis
    - Learned conflict resolution in Git workflows
    - Optimized cloud resource usage for smooth operation

  uniqueness:
    - 100% cloud-based face analysis pipeline
    - Combines ML, computer vision, and AWS tools
    - Fully replicable and free-tier friendly
    - Simple enough for beginners, useful for real-world testing

  how_to_run:
    - Step 1: Run `upload_image_to_s3.py` to capture image from webcam and upload to S3
    - Step 2: Open SageMaker notebook instance and launch JupyterLab
    - Step 3: Run DeepFace analysis in the notebook using downloaded image

  prerequisites:
    - AWS CLI configured
    - S3 bucket created
    - SageMaker instance running (preferably `ml.t3.medium`)

  tools_used:
    - Python
    - OpenCV
    - DeepFace
    - Amazon S3
    - SageMaker
    - GitHub

  final_quote: >
    "Power isn't determined by your size, but the size of your heart and dreams."
