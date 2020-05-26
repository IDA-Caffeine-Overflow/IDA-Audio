Audio is sent to DEEP-LEARNING 7-LAYERED DNN Model , which considers spectrogram of the
audio and uses the Librosa library for classifying the particular emotions Angry, Sad, Disgust,
Surprised, and a testing accuracy of 75%.

The calls are classified based on following features in our DL Model:

### MelSpectrogram, MFCC, Spectral-Contrast, Chroma,Tonnetz

The text is prioritized using TF-IDF, Page Ranking, Cosine Similarity using steps:
