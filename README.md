# Yoga_pose_detection
# 🧘 Yoga Pose Detection Using Deep Learning

## 📌 Project Overview

Yoga Pose Detection is an AI-powered computer vision project designed to identify and classify different yoga postures using deep learning techniques.

The project combines **VGG19 (Convolutional Neural Network)** for yoga pose classification and **MediaPipe** for human pose landmark detection.

It supports two modes of operation:

- **Image-Based Classification:** Upload an image of a person performing yoga, and the system predicts the corresponding yoga pose.
- **Real-Time Detection:** Uses a webcam to capture live video, detect human body landmarks, and recognize yoga poses in real time.

The project demonstrates the application of Artificial Intelligence, Deep Learning, and Computer Vision in fitness and yoga assistance.

## 🎯 Objectives

- Develop an automated yoga pose recognition system.
- Classify different yoga postures using deep learning.
- Implement image-based and real-time yoga pose detection.
- Integrate MediaPipe for human body landmark detection.
- Explore computer vision applications in fitness and healthcare assistance.

## ✨ Key Features

- Image-based yoga pose classification.
- Real-time yoga pose detection using a webcam.
- Deep feature extraction using VGG19.
- Human body landmark detection using MediaPipe.
- Image preprocessing with a resolution of 224 × 224 pixels.
- Recognition of five different yoga poses.

## 🧘 Supported Yoga Poses

The model recognizes the following five yoga poses:

1. Downward Dog
2. Goddess Pose
3. Plank Pose
4. Tree Pose
5. Warrior II Pose

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| VGG19 | Deep learning-based pose classification |
| TensorFlow / Keras | Model development and implementation |
| MediaPipe | Human pose landmark detection |
| OpenCV | Image and video processing |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |

## ⚙️ System Workflow

### 1. Image-Based Yoga Pose Classification

1. Upload an image containing a person performing a yoga pose.
2. Preprocess the image by resizing it to 224 × 224 pixels.
3. Extract visual features using the VGG19 architecture.
4. Pass the processed image through the trained classification model.
5. Display the predicted yoga pose.

### 2. Real-Time Yoga Pose Detection

1. Access the webcam to capture live video frames.
2. Process the video frames using OpenCV.
3. Detect human body landmarks using MediaPipe.
4. Extract the relevant visual features.
5. Predict the yoga pose using the trained VGG19-based model.
6. Display the detected pose on the live video feed.

## 🏗️ Model Architecture

### VGG19
- A deep convolutional neural network architecture.
- Used for extracting visual features from yoga pose images.
- Uses an input image resolution of 224 × 224 pixels.
- Supports classification of five yoga pose categories.

### MediaPipe
- Detects human body landmarks.
- Identifies important body joints and key points.
- Supports real-time human pose analysis.

## 📂 Project Structure

```text
Yoga-Pose-Detection/
│
├── dataset/
│   ├── downdog/
│   ├── goddess/
│   ├── plank/
│   ├── tree/
│   └── warrior2/
│
├── models/
│   └── yoga_pose_model.h5
│
├── notebooks/
│   └── yoga_pose_detection.ipynb
│
├── images/
│   └── output_samples/
│
├── requirements.txt
├── README.md
└── main.py
```

*Note: Update the folder and file names to match your actual repository structure.*

## 🚀 Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Directory

```bash
cd Yoga-Pose-Detection
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Project

```bash
python main.py
```

*Note: Replace the execution command with the appropriate command for your project.*

## 💡 Applications

- Automated yoga pose recognition.
- AI-powered fitness applications.
- Yoga learning and practice assistance.
- Human activity recognition.
- Computer vision-based fitness monitoring.

## 🔮 Future Enhancements

- Yoga posture correction using body landmark analysis.
- Real-time feedback on incorrect yoga postures.
- Yoga performance scoring.
- Repetition counting functionality.
- Support for additional yoga poses.
- Development of a user-friendly web or mobile application.

## 👩‍💻 Author

**Divya Chethana**

B.E. – Artificial Intelligence and Data Science

Interested in Artificial Intelligence, Machine Learning, Deep Learning, and Computer Vision.

## ⭐ Acknowledgements

- TensorFlow and Keras
- Google MediaPipe
- OpenCV
- VGG19 Architecture

---

If you find this project interesting, consider giving the repository a ⭐!
