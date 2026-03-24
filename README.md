# Face Emotion Detection 🎭

A real-time facial emotion recognition system powered by Deep Learning (CNN) and OpenCV. This project detects human faces from a webcam feed and classifies their expressions into one of seven emotional categories.

## 🌟 Features

- **Real-time Detection**: Captures video from your webcam and identifies emotions on the fly.
- **Deep Learning Model**: Uses a Convolutional Neural Network (CNN) trained on facial expression data.
- **Multi-Face Support**: Capable of detecting and labeling multiple faces simultaneously.
- **Seven Emotion Categories**:
  - 😠 Angry
  - 🤢 Disgust
  - 😨 Fear
  - 😊 Happy
  - 😐 Neutral
  - 😢 Sad
  - 😲 Surprise

## 📂 Project Structure

- `detection.py`: The main Python script for real-time emotion detection via webcam.
- `trainmodel.ipynb`: Jupyter Notebook containing the code for model training and evaluation.
- `emotiondetector.h5`: The pre-trained Keras model weights.
- `emotiondetector.json`: The model architecture in JSON format.
- `requirements.txt`: List of Python dependencies required to run the project.
- `images/`: Directory containing the training and testing datasets.

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Webcam (for real-time detection)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/praveenlokku/Face-Emotion-Detection.git
   cd Face-Emotion-Detection
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

#### Real-time Detection
Run the following command to start the webcam-based emotion detector:
```bash
python detection.py
```
- Press **'q'** to exit the application.

#### Training the Model
If you wish to retrain or modify the model, open the Jupyter Notebook:
```bash
jupyter notebook trainmodel.ipynb
```

## 🛠️ Built With

- **TensorFlow/Keras**: For building and running the Deep Learning model.
- **OpenCV**: For real-time image processing and face detection.
- **NumPy**: For numerical operations.
- **Matplotlib**: For visualizing training progress.



---
*Created by [Praveen Lokku](https://github.com/praveenlokku)*
