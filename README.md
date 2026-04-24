AI-Based Animal Type Classification System

📌 Overview

This project is an AI-powered system that classifies animals (Cattle vs Buffalo) from images and performs object detection and basic measurement estimation. It combines deep learning (CNN), computer vision, and a full-stack web application to deliver predictions through an easy-to-use interface.

🚀 Features

Image classification (Cattle vs Buffalo) using CNN
Object detection using YOLO
Image preprocessing with OpenCV
Measurement estimation from detected objects
FastAPI backend for handling model inference
Web-based frontend for user interaction

🧠 Technologies Used

Machine Learning & CV:
CNN (Convolutional Neural Networks)
YOLO (You Only Look Once)
OpenCV

Backend:
FastAPI (Python)

Frontend:
HTML
CSS
TypeScript

Others:
Docker (for containerization)

📂 Project Structure

backend/ 
core_ml/     
docker/  
frontend/
create_project_zip.py
Docker-compose.yml
README.md


📥 Project Files (Google Drive)

Due to file size limitations, the complete project files (dataset and trained models) are hosted on Google Drive:

🔗 https://drive.google.com/drive/folders/1-RJjBfjz95IT6Atw862pPX5sPpYlguNt?usp=sharing

Note: Download and extract the files before running the project.

⚙️ Installation
1.Clone the repository:
git clone <your-repo-link>
cd animal-classification
2.Install dependencies:
pip install -r requirements.txt

▶️ Usage

1.Start backend server:
uvicorn main:app --reload

2.Run frontend (if separate setup required)

3.Upload an image via UI

4.Get classification + detection results

📊 Model Details

CNN model trained on labeled cattle and buffalo images
YOLO used for detecting animal regions in images
OpenCV used for preprocessing and image handling

📈 Results

High accuracy in classification
Reliable object detection
Stable performance across multiple test cases

🔮 Future Enhancements

Add more animal categories
Improve detection accuracy
Mobile app integration
Real-time camera-based detection

👨‍💻 Author

J Vidyadhar

This project bridges AI and livestock management, improving efficiency and decision-making using modern technology.
