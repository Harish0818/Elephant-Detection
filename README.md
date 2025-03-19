# 🐘 Real-Time Elephant Detection using YOLOv5 & Faster R-CNN

## 🚀 Overview
Designed a real-time **elephant detection system** to mitigate human-elephant conflicts and prevent property damage. The system utilizes advanced image processing techniques, including **Convolutional Neural Networks (CNNs), YOLO, and Faster R-CNN**, for accurate detection and classification of elephants.

### 🔹 **Key Features**
✅ **Real-time detection using YOLOv5 & Faster R-CNN**  
✅ **Achieved 89% accuracy with YOLO and 92% with Faster R-CNN**  
✅ **Data augmentation & transfer learning (ResNet, EfficientNet)**  
✅ **Hyperparameter tuning for improved accuracy**  
✅ **Early warning system for human-wildlife coexistence**  

## 📷 Sample Output
### 🖼️ Image Detection Example:
<img width="645" alt="image" src="https://github.com/user-attachments/assets/6f439925-f00f-4a29-84d4-f5c2e8ebb178" />


## ⚙️ Installation
### Step 1: Clone the Repository
git clone https://github.com/your-username/yolov5-elephant-detection.git
cd yolov5-elephant-detection

### Step 2: Install Dependencies
pip install -r requirements.txt

### Step 3: Download YOLOv5 Model
wget https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5s.pt -O models/yolov5s.pt

### Step 4: Run Object Detection
## For Images
python main.py --source data/input_image.jpg

## For Video Files
python main.py --source data/input.mp4

