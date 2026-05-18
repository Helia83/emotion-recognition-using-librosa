# emotion-recognition-using-librosa
This project is a simple Speech Emotion Recognition (SER) system built using Python, Librosa, and Machine Learning.

The model extracts audio features from speech signals and predicts the speaker's emotion using a Random Forest Classifier.

# Features

* Audio feature extraction using Librosa
* MFCC feature analysis
* RMS Energy extraction
* Zero Crossing Rate (ZCR) analysis
* Feature normalization using StandardScaler
* Emotion classification using Random Forest

# Emotions Supported

* Happy
* Sad
* Angry
* Neutral

# Technologies Used

* Python
* Librosa
* NumPy
* Scikit-learn
  
# How It Works

1. Load audio files using Librosa
2. Extract important speech features:
   * RMS Energy
   * Zero Crossing Rate
   * MFCC coefficients
3. Normalize extracted features
4. Train a Random Forest classifier
5. Predict emotion from a new audio file

## Future Improvements

* Add larger emotion datasets
* Improve model accuracy
* Use Deep Learning models such as CNN or LSTM
* Build a real-time emotion recognition system

## Author

Created by Helia using Librosa and Machine Learning.
