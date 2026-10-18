
# Marvellous Real-Time Image Classification

A real-time image classification application built using Python, TensorFlow, MobileNetV2, and OpenCV. The project uses a pretrained CNN model to identify objects captured through a live webcam feed.

## Features

- Real-time object classification using a webcam
- Pretrained MobileNetV2 deep learning model
- Image preprocessing using TensorFlow/Keras
- Prediction labels with confidence scores
- Live prediction display using OpenCV
- Simple keyboard control to exit the application

## Technologies Used

- Python
- TensorFlow / Keras
- MobileNetV2
- OpenCV
- NumPy
- ImageNet pretrained weights

## Project Workflow

1. Load the pretrained MobileNetV2 model with ImageNet weights.
2. Capture live video frames using the webcam.
3. Convert frames from BGR to RGB.
4. Resize each frame to 224 × 224 pixels.
5. Preprocess the image for MobileNetV2.
6. Predict the object category using the model.
7. Display the predicted label and confidence score on the video feed.

## Project Structure

```text
Marvellous-Realtime-Image-Classification/
├── Marvellous_Realtime_Image_Classification.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Marvellous-Realtime-Image-Classification.git
cd Marvellous-Realtime-Image-Classification
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows Command Prompt:

```cmd
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python Marvellous_Realtime_Image_Classification.py
```

Ensure your webcam is connected and accessible. Press **q** to exit the application.

## Model Information

This project uses MobileNetV2 pretrained on ImageNet. The model predicts categories from its pretrained ImageNet classes and displays the top prediction with its confidence score.

The pretrained model weights may be downloaded automatically during the first run if they are not already available locally.

## Future Improvements

- Display the top five predicted classes
- Add frames-per-second (FPS) monitoring
- Improve prediction visualization
- Develop a graphical user interface
- Support custom-trained image classification models

## License

This project is intended for educational and learning purposes.
