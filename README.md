# 🚧 Road Damage Detection Using YOLO

## 📌 Project Overview
Road Damage Detection is a Computer Vision project that uses YOLO to detect damaged areas on roads. The model identifies road damage in images and displays bounding boxes around detected regions.

## 🎯 Objectives
- Detect road damage using deep learning.
- Identify damaged areas with bounding boxes.
- Evaluate model performance using Precision, Recall, and mAP.
- Visualize training and validation graphs.
- Create a simple Gradio web interface for testing images.

## 📂 Dataset
**Dataset Link:** [Roboflow Road Damage Detection Dataset](https://universe.roboflow.com/capstone-nh0nc/car-damage-detection-t0g92/dataset/4)

## 🛠️ Technologies Used
- Python
- Google Colab
- YOLO (Ultralytics)
- OpenCV
- Matplotlib
- Gradio
- Roboflow

## ⚙️ Project Workflow
1. Download and prepare the dataset.
2. Load the dataset configuration YAML file.
3. Train the YOLO object detection model.
4. Evaluate the model using Precision, Recall, and mAP.
5. Display training and validation graphs.
6. Generate a confusion matrix.
7. Test the model on new road images.
8. Deploy the model using Gradio.

## 📊 Model Evaluation
- **Precision:** Measures how many predicted damage detections are correct.
- **Recall:** Measures how many actual damage instances are detected.
- **mAP50:** Measures detection performance at an IoU threshold of 0.50.
- **mAP50-95:** Measures detection performance across multiple IoU thresholds.
- **Confusion Matrix:** Shows correct and incorrect class predictions.

## 📦 Bounding Box Detection
The model draws bounding boxes around detected damaged areas. Each box indicates the predicted damage class and its location in the image.

## 🌐 Gradio Interface
The Gradio interface allows users to upload a road image and view the predicted road damage with bounding boxes.

## ✅ Conclusion
This project demonstrates how Computer Vision and YOLO can be used for road damage detection. It includes dataset preparation, model training, evaluation, visualization, and an interactive interface.

## 👨‍💻 Author
**Daniyal**
