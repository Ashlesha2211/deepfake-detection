# Deepfake Detection System

## Overview
The Deepfake Detection System is a machine learning project designed to identify manipulated or AI-generated media. The system analyzes facial features and visual inconsistencies in images/videos to classify content as real or fake.

This project aims to combat misinformation and improve the authenticity of digital media using deep learning and computer vision techniques.

## Features
- Detects manipulated and deepfake content
- Automated image/video preprocessing
- Face extraction and normalization
- Deep learning-based classification
- Performance evaluation using accuracy metrics and confusion matrix
- Handles diverse media sources

## Technologies Used
- Python
- PyTorch
- OpenCV
- NumPy
- Pandas
- Matplotlib
- CNN (Convolutional Neural Networks)
- LSTM (Long Short-Term Memory Networks)

## Project Workflow
1. Collect and prepare dataset
2. Extract frames from videos
3. Detect and crop faces
4. Preprocess and normalize images
5. Train CNN model for spatial feature extraction
6. Apply LSTM for temporal sequence analysis
7. Evaluate model performance
8. Predict whether media is real or fake

## Model Architecture
- ResNeXt50-based CNN for feature extraction
- LSTM network for temporal sequence modeling
- Binary classification (Real vs Deepfake)

## Results
The model successfully identifies deepfake content by learning facial patterns and inconsistencies across frames. Performance was evaluated using:
- Accuracy Score
- Loss Curves
- Confusion Matrix
- Precision and Recall Metrics

## Project Structure

```
Deepfake-Detection/
│
├── dataset/
├── notebooks/
├── models/
├── outputs/
├── images/
├── requirements.txt
├── deepfake_detection.ipynb
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Deepfake-Detection.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

## Future Enhancements
- Real-time deepfake detection
- Web-based user interface
- Support for multiple deepfake datasets
- Improved accuracy using transformer-based models
- Deployment on cloud platforms

## Author

**Ashlesha Gawkar**

B.Tech Computer Science Engineering  
MIT World Peace University (MIT-WPU)
