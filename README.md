# Real-Time Gender Detection

This project implements a real-time gender detection system using an 11-layer Convolutional Neural Network (CNN) architecture, seamlessly integrated with OpenCV for live detection. The exceptional performance of the model is attributed to its training with a diverse dataset consisting of over 1000 images, resulting in an impressive accuracy rate of 95%.

## Requirements

Before running the gender detection system, ensure you have the following dependencies installed:

- Python 3.x
- OpenCV
- NumPy
- TensorFlow or Keras

## Installation

1. Clone this repository to your local machine.
```
git clone https://github.com/your_username/real-time-gender-detection.git
```

2. Install the required Python packages.
```
pip install opencv-python numpy tensorflow
```

## Usage

To use the real-time gender detection system:

1. Run the `gender_detection.py` script.
```
python gender_detection.py
```

2. The system will access your webcam and start real-time gender detection.
3. The detected gender (male or female) will be displayed on the screen alongside the video feed.

## Dataset

The model was trained on a diverse dataset of over 1000 images, containing equal representations of male and female faces. This comprehensive dataset ensures accurate gender detection across various ethnicities and age groups.

## Performance

Thanks to the carefully curated dataset and the well-designed 11-layer CNN architecture, the model exhibits exceptional performance, achieving an impressive accuracy rate of 95%. It can swiftly and accurately identify gender from real-time video feeds
---
Feel free to customize and expand the above README according to your project's specifics. Make sure to include relevant details about the implementation, data preprocessing, model architecture, and any other significant aspects.
