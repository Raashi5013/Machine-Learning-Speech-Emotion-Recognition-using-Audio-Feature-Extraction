Machine-Learning-Speech-Emotion-Recognition-using-Audio-Feature-Extraction
This Speech Emotion Recognition (SER) project focuses on identifying human emotions from speech audio signals using machine learning techniques. The system classifies audio recordings into one of eight emotional categories: Angry, Sad, Happy, Neutral, Calm, Fearful, Disgust, and Surprised. It leverages the RAVDESS dataset, which provides professionally recorded audio clips with clear emotional articulation from 24 actors. The primary goal of the project is to build a reliable classifier that can detect emotions from speech, which has practical applications in areas such as mental health diagnostics, virtual assistants, customer service automation, and human-computer interaction.

The core of the project lies in audio feature extraction, where powerful characteristics such as MFCC (Mel Frequency Cepstral Coefficients), Chroma, Mel Spectrogram, Spectral Contrast, and Tonnetz are extracted from each audio sample using the Librosa library. These features represent the timbre, pitch, rhythm, and tonal content of speech, which are critical for emotion detection. After feature extraction, the data is preprocessed using standardization and label encoding, and the dataset is balanced across all emotion classes.

Three machine learning models were implemented: a Multi-Layer Perceptron (MLP), Support Vector Machine (SVM), and K-Nearest Neighbors (KNN). Among these, MLP was fine-tuned using RandomizedSearchCV for optimal performance. K-Fold Cross Validation was also used to ensure the models' generalization and robustness. The models were evaluated using metrics like accuracy, precision, recall, F1-score, and confusion matrix. 

This project was developed using Python and key libraries such as Librosa for audio processing, scikit-learn for machine learning, NumPy and Pandas for data handling, and Seaborn/Matplotlib for visualization. 
The structured workflow — from loading and processing audio files to training models and evaluating results — makes this project reproducible and extensible. 


