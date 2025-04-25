# Autotune-Classification

🎶 Autotune Audio Classification with Machine Learning
This project focuses on classifying music audio recordings based on the use of autotune by applying various audio feature extraction techniques and machine learning algorithms.

📁 Dataset
The dataset consists of 426 .wav audio files (275 autotuned, 151 non-autotuned) sourced via web scraping from Freesound.org. The audio samples were resampled to 44.1kHz and balanced using SMOTE to address class imbalance.

🔍 Feature Extraction
We extracted several spectral features using Librosa, including:

MFCC (Mel-Frequency Cepstral Coefficients) – represents spectral envelope.

Spectral Centroid – indicates the "brightness" of audio.

Chroma – captures harmonic and pitch-related features. These features were also combined to improve model performance.

🧠 Machine Learning Models
Three classification models were used:

Random Forest

Support Vector Machine (SVM)

Multi-Layer Perceptron (MLP)

Each was trained on different feature combinations and evaluated using accuracy, precision, recall, and F1-score.

🏆 Results
Random Forest achieved the best performance with 90% accuracy using the combination of MFCC, Spectral Centroid, and Chroma.

Chroma feature individually provided outstanding performance across models.

Feature selection played a key role, where model performance varied depending on feature combinations.

🔗 Resources
Dataset

EDA Notebook

Modeling Notebook
