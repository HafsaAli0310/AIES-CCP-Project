# AIES-CCP-Project
## POTHOLE DETECTOR:
This project is a Convolutional Neural Network (CNN)-based pothole detection system built using TensorFlow and OpenCV. It supports pothole detection on images, videos, and real-time webcam feeds.

## Group Members
Hafsa Ali (CR-22006)
Dania Fazal (CR-22007)

## 📌 Features
- Binary image classification: `Pothole` vs. `No Pothole`
- CNN model built with TensorFlow/Keras
- Detection from:
  - Single image
  - Video files
  - Webcam feed
- Visual display with bounding boxes and labels

## How to run?
### 1. Clone the github repository
   - git clone https://github.com/HafsaAli0310/AIES-CCP-Project.git
   - cd AIES-CCP-Project
    
### 2. Make sure you have the required libraries installed
   - TensorFlow / Keras
   - OpenCV
   - NumPy
   - scikit-learn

### 3. In python file, update the following paths:
   - pothole_dir = 'Path to folder of pothole_pics'
   - no_pothole_dir = 'Path to folder of other_pics'
   - image_path = 'Path to test_image4.jpg'
   - video_path = 'Path to test_video5.mp4'

   - Then run:
      - python filename.py
