# 🎵 Music Genre Classification System

**[🚀 CLICK HERE TO TRY THE LIVE WEB APP!]https://musicgenreclassification-fpyqywt6zb7f4g2upihvxs.streamlit.app/**

An end-to-end **Deep Learning project** that classifies music into different genres using raw audio data.

This system converts audio signals into visual representations (**Mel-Spectrograms**) and uses a **Convolutional Neural Network (CNN)** for accurate predictions.

The trained model is deployed as an interactive **Streamlit web application**.

---

## 🚀 Features

- 🎧 Upload `.wav` audio files  
- ⚡ Real-time genre prediction  
- 🧠 CNN-based deep learning model  
- 🎨 Audio-to-image transformation using Mel-Spectrograms  
- 🌐 Simple and interactive UI  

---

## 🧠 How It Works

### 1. Audio Preprocessing
- Loads `.wav` files using `librosa`
- Splits audio into **4-second overlapping chunks**
- Improves dataset size and consistency

### 2. Spectrogram Generation
- Uses **Fast Fourier Transform (FFT)**
- Converts audio → frequency vs time representation

### 3. Mel-Spectrogram Conversion
- Converts frequencies to **Mel scale**
- Matches human hearing perception

### 4. Data Formatting
- Resized to `(150, 150, 1)`
- Used as grayscale image input for CNN

---

## 🏗️ Model Architecture

Built using **TensorFlow / Keras**

- **Convolutional Layers** → Extract audio patterns  
- **MaxPooling Layers** → Reduce dimensions  
- **Flatten Layer** → Convert 2D → 1D  
- **Dense Layers** → Classification  
- **Softmax Output** → Predicts 10 genres  

---

## 🎯 Genres

- Jazz  
- Blues  
- Pop  
- Metal  
- Classical  
- Hip-Hop  
- Rock  
- Disco  
- Country  
- Reggae  

---

## 🌐 Web App (Streamlit)

- Upload audio file  
- Automatic preprocessing  
- Instant prediction  
- Clean UI  

---


---

## 🛠️ Tech Stack

- Python  
- TensorFlow / Keras  
- Librosa  
- NumPy, Pandas  
- Matplotlib  
- Streamlit  

---

## Download from:

https://drive.google.com/file/d/1hoL_DLAnycV9uoQDaFMXUFGHlv6y85ys/view?usp=sharing

Place `Trained_model.h5` in root folder.

---

###  Run App

```bash
streamlit run Music_app.py
```

Open in browser:

http://localhost:8501

---

