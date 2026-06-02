```text
							With Love  ⣠⣶⣶⣶⣦⠀⠀
							⠀⠀⣠⣤⣤⣄⣀⣾⣿⠟⠛⠻⢿⣷⠀
							⢰⣿⡿⠛⠙⠻⣿⣿⠁⠀⠀⠀⣶⢿⡇
							⢿⣿⣇⠀⠀⠀⠈⠏⠀⠀⠀ By Junaid
							⠀⠻⣿⣷⣦⣤⣀⠀⠀⠀⠀⣾⡿⠃⠀
							⠀⠀⠀⠀⠉⠉⠻⣿⣄⣴⣿⠟⠀⠀⠀
							⠀⠀⠀⠀⠀⠀⠀⣿⡿⠟⠁⠀⠀⠀⠀
```


# Emotion Detector Music Recommender

An AI-powered music recommendation system that detects user emotions in real time using webcam-based facial landmark analysis and recommends songs accordingly.

Built using:
- Streamlit
- MediaPipe
- TensorFlow/Keras
- OpenCV

---
<img width="1244" height="641" alt="Screenshot 2026-06-02 152631" src="https://github.com/user-attachments/assets/591becdb-3115-458b-8534-1e166bc6294a" />
Kinda cool, right? : )
## Features

- Real-time webcam emotion detection
- Facial landmark tracking using MediaPipe
- Deep learning emotion classification model
- Song recommendation based on:
  - detected emotion
  - preferred language
  - favorite singer/artist
- Interactive Streamlit web interface
- Automatic YouTube song search integration

---

## How It Works

1. Webcam captures live video feed
2. MediaPipe extracts facial and hand landmarks
3. Landmark data is processed by a trained Keras model
4. Emotion is predicted in real time
5. User enters:
   - preferred language
   - singer/artist
6. App recommends songs matching the detected emotion

---

## Tech Stack

- Python
- Streamlit
- OpenCV
- MediaPipe
- TensorFlow / Keras
- NumPy

---

## Project Structure

```text
Emotion_detector_music_rcmdr
├── app.py
├── emotion.npy
├── labels.npy
├── model.h5
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone <repo-url>
cd Emotion_detector_music_rcmdr
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## Model Details

- `model.h5` → Trained emotion classification model
- `labels.npy` → Emotion labels/classes
- `emotion.npy` → Stores latest detected emotion

---

## Workflow

```text
Webcam Feed
     ↓
MediaPipe Landmark Detection
     ↓
Feature Extraction
     ↓
Keras Emotion Classification
     ↓
Emotion-Based Song Recommendation
     ↓
YouTube Search Results
```

---

## Future Improvements

- Spotify API integration
- Mood history tracking
- Better recommendation engine
- Multiple emotion detection
- User authentication
- Emotion analytics dashboard
- Playlist generation

---

## Sample Emotions Detected

- Happy
- Sad
- Angry
- Neutral
- Surprise

---

## Requirements

Typical dependencies include:

```text
streamlit
streamlit-webrtc
opencv-python
mediapipe
tensorflow
keras
numpy
av
```

---

## Notes

- Webcam access is required
- Stable lighting improves detection accuracy
- Model accuracy depends on training dataset quality

---

## Author

Built by Junaid
