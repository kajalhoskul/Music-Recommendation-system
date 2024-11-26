# Emotion-Based Smart Music Player 🎵

The Emotion-Based Smart Music Player is a Python application that uses facial recognition and emotion detection to play music based on the user's mood. By analyzing real-time input from a webcam, it identifies emotions such as *happy*, *sad*, *angry*, and *neutral*, and plays corresponding music tracks.

---

## Features

- **Real-time Emotion Detection**: Recognizes facial emotions using OpenCV and FisherFace models.
- **Mood-Based Music Playback**: Automatically plays music matching your detected mood.
- **Custom Model Training**: Update the emotion detection model using your own dataset.
- **Interactive UI**: A lightweight graphical interface powered by Eel.
- **Dataset Creation**: Captures user images for training and improves model accuracy.

---

## Prerequisites

1. **Python Libraries**:
   - `opencv-python`
   - `numpy`
   - `eel`
   - `argparse`
   - `os`
   - `glob`
   - `random`
   - `time`
   - `winsound`

2. **Pre-trained Model**:
   - A FisherFace model file (`model.xml`). If missing, you can train a new one using the `--update` option.

3. **Hardware Requirements**:
   - A webcam for real-time face and emotion detection.

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd emotion-based-smart-music-player

