# Elephant-Bear-Detection-Model-using-Yolov10
YOLOv10-N, built on the Ultralytics Python package, is optimized for real-time object detection in resource-constrained environments. By eliminating non-maximum suppression and optimizing model components, Ideal for houses near forests, it can alert people about wild animal attacks like elephants and bears.
Requirements for Elephant & Bear Detection Model Using YOLOv10-N
1. Hardware:
GPU: GeForce GTX 1650 with 4GB VRAM
CPU: Modern multi-core processor
RAM: Minimum 8GB, recommended 16GB or higher
Storage: Sufficient space for dataset and model storage (at least 50GB)
![Screenshot 2024-07-20 222832](https://github.com/user-attachments/assets/8d71b7f8-948a-4a1f-aa11-4e0f0edbe3a0)



3. Software:
Operating System: Windows 10/11, Ubuntu 20.04 or later
Python Version: Python 3.10 or later
Dependencies:
Ultralytics Python package
Torch (PyTorch)
CVAT for image annotation

5. Dataset:
Source: Kaggle wild animal dataset
Content: Images and videos of wild animals, specifically bears and elephants
Annotation Tool: CVAT (Computer Vision Annotation Tool)
6. Model:
Framework: YOLOv10-N (Nano version)
Features:
Real-time object detection
No Non-Maximum Suppression (NMS)
Optimized architecture for resource-constrained environments
7. Environment Setup:
Python Libraries Installation:
bash
Copy code
pip install ultralytics opencv-python numpy pandas torch
CVAT Setup:
Install and configure CVAT for annotating the dataset.
8. Training:
Training Environment: Preferably on a GPU-enabled machine
Dataset Preparation: Annotate the images using CVAT and format them as required by YOLOv10-N
Model Training: Use the YOLOv10-N framework for training on the annotated dataset
Hyperparameters:
Batch size
Learning rate
Number of epochs = 350
