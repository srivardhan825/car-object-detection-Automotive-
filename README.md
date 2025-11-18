🚗 Vehicle Speed Detection using Computer Vision & Deep Learning

This project detects vehicles in a video stream and calculates their speed using Computer Vision, OpenCV, and Deep Learning models such as Faster R-CNN / YOLO.
It is designed for real-time traffic monitoring, smart transportation systems, and road safety applications.

🔍 Features

Detects vehicles (car, bike, bus, truck)

Tracks each vehicle across video frames

Calculates speed using distance covered per frame

Works with CCTV footage or live camera

Supports deep-learning detectors (YOLO / Faster R-CNN)

Real-time visualization of:

Bounding boxes

Vehicle ID

Estimated speed

🧠 Models Used

You can use any of the following:

Faster R-CNN (PyTorch)

YOLOv8 (Ultralytics)

Both models offer high accuracy for object detection.

📦 Project Requirements
Software Requirements

Python 3.8 – 3.11

OpenCV

PyTorch

Torchvision

NumPy

Matplotlib

Ultralytics (optional, for YOLO)

Supervision (optional, for tracking)

Python Libraries
opencv-python
torch
torchvision
numpy
matplotlib
pillow
scipy
tqdm
ultralytics
supervision

NVIDIA GPU (GTX 1050 Ti or higher)

▶️ How to Run
# Install required libraries
pip install -r requirements.txt

# Run the project
python speed_detection.py

📌 Methodology

Object detection model identifies vehicles per frame

Vehicle IDs tracked using centroid tracking

Distance moved between frames is calculated

Speed is derived using:

speed = distance / time


Final video is rendered with bounding boxes + speed labels

🎯 Output

The output video will contain:

Vehicle bounding boxes

Tracking ID

Calculated speed (km/h or mph)

📚 Use Cases

Traffic monitoring

Smart city applications

Accident analysis

Highway speed enforcement

Transport research

🏁 Conclusion

This project successfully detects and tracks vehicles in video streams and calculates their speed using deep learning. It can be integrated with real-time CCTV systems for traffic management and road safety improvement.
