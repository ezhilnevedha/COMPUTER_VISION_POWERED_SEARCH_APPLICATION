# COMPUTER_VISION_POWERED_SEARCH_APPLICATION
## BY EZHIL NEVEDHA K
This project is a Computer Vision–powered search application that allows users to upload an image and retrieve similar images or detect objects from the image. It uses a trained YOLO model for inference and a simple UI built with Streamlit.

### Features

Upload an image and perform object detection

Search for similar images based on detected objects

Real-time inference using YOLO

Simple and user-friendly interface

Auto GPU/CPU selection for faster performance

### Project Structure
```
project/
│── app.py                         # Main Streamlit application
|── requirements.txt               # All required packages
│── src/                                            
│    ├── inference.py              # YOLO model loading & prediction
│    ├── config.py                 # Configuration loader
│── models/
│    └── your_model.pt             # YOLO model weight file
│── assets/
     └── sample_images/            # Demo images
```
### How It Works

The user uploads an image

YOLO runs inference and detects objects

The app displays the detected objects with bounding boxes

(Optional) The detected labels are used to perform a search or recommendation

### Technologies Used

Python

YOLO (Ultralytics)

Streamlit

OpenCV

NumPy, Pandas

### Output:
<img width="1919" height="964" alt="Screenshot 2025-11-19 091637" src="https://github.com/user-attachments/assets/92c812b5-f545-471c-ab09-53a7465365e5" />

<img width="1919" height="967" alt="image" src="https://github.com/user-attachments/assets/e91d740e-9e89-4d13-9129-cbfe392d643b" />

<img width="1601" height="658" alt="image" src="https://github.com/user-attachments/assets/eecdcaab-0a5b-45e3-a2ed-4f019dbbdc85" />


