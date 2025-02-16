## 📌 Overview
The project focuses on lip reading from audioless video using deep learning techniques. The system processes video frames, converts them into grayscale, and extracts relevant mouth movement data. It utilizes a vocabulary-based character mapping system to interpret speech from visual cues. A deep neural network, including Conv3D, LSTMs, and Bidirectional layers, is trained to predict spoken words from silent videos. The project includes a data pipeline for loading and aligning videos with text, model training with CTC loss, and evaluation on test samples. The final model achieves accurate predictions, demonstrating its potential for silent communication and accessibility applications.
# Lip Reading using LipNet


## ✨ Features
- **End-to-End Deep Learning Model**: Uses CNN and LSTM for accurate lip reading.
- **Pretrained & Custom Training Support**: Train on public datasets like **GRID** or use custom datasets.
- **Real-Time Inference**: Process video sequences to predict spoken words.
- **TensorFlow & PyTorch Support**: Uses deep learning frameworks for efficient computation.
- **Dataset Preprocessing**: Includes video frame extraction and alignment.

## 🛠️ Technologies Used
- **Python**
- **TensorFlow / PyTorch**
- **OpenCV** (for video processing)
- **NumPy & Pandas** (for data handling)
- **Matplotlib & Seaborn** (for visualization)
- **FFmpeg** (for video conversion)

## 📂 Dataset
- The project supports the **GRID dataset** for training.
