
## Face Detection

## Description
This Python code leverages InceptionV3 for feature extraction and Haar cascades for face detection in real-time webcam video. It highlights detected faces with green rectangles, providing an interactive face recognition system that responds to user input, making it engaging and visually appealing.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
  - [Image Collection](#image-collection)
  - [Face Recognition](#face-recognition)
  - [Training the Model](#training-the-model)
- [Acknowledgements](#acknowledgements)

## Installation
To set up your development environment and install the required dependencies, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/himanshu-commits/Face-Detection.git
   cd Face-Detection
   ```

2. Install the necessary Python packages:
   ```bash
   pip install numpy
   pip install pandas
   pip install matplotlib
   pip install seaborn
   pip install keras
   pip install tensorflow
   pip install opencv-python
   pip install pillow
   pip install requests
   pip install scikit-learn
   ```

## Usage

### Image Collection
To collect images for face recognition using OpenCV, run the following script:
```bash
python FaceSeamlessnetry.ipynb
```

This script utilizes OpenCV to capture frames from the webcam, detects faces, and saves cropped faces to a specified directory.

### Face Recognition
To run the face recognition system, execute the following script:
```bash
python face_frontend_model.ipynb
```

The script uses a pre-trained face recognition model to predict whether a face is present in the webcam feed.

### Training the Model
If you want to retrain the face recognition model, use the following command:
```bash
python face_recognition_model.ipynb
```

This script implements transfer learning with a VGG16 model on your dataset. The trained model is saved for future use.


## Acknowledgements
[List any acknowledgements or credits for third-party libraries, resources, or inspiration. Include links or references.]

- [OpenCV](https://opencv.org/)
- [Keras](https://keras.io/)
- [VGG16 Model](https://keras.io/api/applications/vgg/)
