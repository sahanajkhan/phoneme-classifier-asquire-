# 🎙️ Phoneme Classifier using CNN & Mel Spectrograms

This project implements a **Convolutional Neural Network (CNN)** to classify phonemes from audio data.  
The audio is converted into **Mel spectrograms** and then used as input for training the model.

---

## 📌 Features
- Converts audio into Mel spectrograms using **Librosa**.
- Trains a **CNN** model in **PyTorch** for phoneme classification.
- Supports **12 phoneme classes**.
- Generates classification metrics (accuracy, F1-score, confusion matrix).

---

## 📂 Dataset Structure
dataset/
│
├── phoneme1/
│ ├── audio1.mp3
│ ├── audio2.mp3
│ └── ...
├── phoneme2/
│ └── ...


## ⚙️ Installation
Clone the repository:
```bash
git clone https://github.com/yourusername/phoneme-classifier.git
cd phoneme-classifier


pip install -r requirements.txt


jupyter notebook Phoneme_Classifier.ipynb
