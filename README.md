# Human Activity Recognition (CNN + LSTM)

## Overview
Developed a deep learning-based Human Activity Recognition system using a CNN-LSTM (LRCN) architecture to classify activities from video data.

The model captures spatial features using CNN and temporal dependencies using LSTM, enabling accurate activity classification.

## Problem Statement
Recognizing human activities from video data is challenging due to variations in motion, lighting, and execution styles. This project addresses these challenges using deep learning techniques.

## Features
- Video-based activity recognition  
- Spatial feature extraction using CNN  
- Temporal sequence learning using LSTM  
- End-to-end deep learning pipeline  
- Supports multi-class activity classification  

## Architecture
1. Extract frames from video sequences  
2. Normalize and preprocess frames  
3. Use CNN to extract spatial features  
4. Feed features into LSTM for temporal learning  
5. Classify activity using dense layers  

## Dataset
- UCF50 dataset (50 activity classes)  
- Dataset not included due to size constraints  

## Results
- Achieved ~75–80% classification accuracy  
- Effective spatial-temporal feature learning  

## Tech Stack
- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  

## Demo
Add sample videos in the `sample_videos/` folder.

Colab Notebook:
https://colab.research.google.com/drive/1RtTYonaJ7ASX_ZMzcV3t_0jNktheKQF9

## Future Improvements
- Real-time activity detection  
- Improve accuracy with larger datasets  
- Deploy as web application  
