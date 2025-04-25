# Autotune Audio Classification with Machine Learning

This project focuses on classifying music audio recordings based on the use of autotune by applying various audio feature extraction techniques and machine learning algorithms.

Dataset : The dataset consists of 426 .wav audio files (275 autotuned, 151 non-autotuned) sourced via web scraping from Freesound.org. The audio samples were resampled to 44.1kHz and balanced using SMOTE to address class imbalance.

## 🔍 Feature Extraction
We extracted several spectral features using Librosa, including: MFCC (Mel-Frequency Cepstral Coefficients), Spectral Centroid, Chroma. 

## 🧠 Machine Learning Models
Three classification models were used: Random Forest, Support Vector Machine (SVM), and Multi-Layer Perceptron (MLP)
Each was trained on different feature combinations and evaluated using accuracy, precision, recall, and F1-score.

## 🏆 Results
Random Forest achieved the best performance with 90% accuracy using the combination of MFCC, Spectral Centroid, and Chroma. Chroma feature individually provided outstanding performance across models.

## 🔗 Resources
[Dataset](https://drive.google.com/drive/folders/1POPfZS0UT0eG81eBgj1WcGP1mXbXfoLH)
[EDA Notebook](https://colab.research.google.com/drive/1W4ETwOajd-FEA4onbdyGkXQyHLPp8KiO)
[Modeling Notebook](https://colab.research.google.com/drive/185OlSFzcBgCdZBKSw_kgeh0TkhXa0Onk?usp=sharing)
