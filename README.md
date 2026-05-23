# 🛡️ Deepfake Defender Pro

Deepfake Defender Pro is an AI-powered deepfake image detection system developed using deep learning and digital forensic analysis techniques.  
The project is designed to detect manipulated or AI-generated facial images with high accuracy using an ensemble learning approach.

The system combines a Custom CNN model and MobileNetV2 Transfer Learning model to improve prediction reliability and performance.  
Along with AI-based detection, the application also performs forensic analysis including Error Level Analysis (ELA), edge detection, metadata inspection, and histogram analysis.

---

## 🚀 Features

- 🔍 AI-based Deepfake Image Detection
- 🧠 Ensemble Learning using CNN + MobileNetV2
- 📷 Image Upload and URL-based Detection
- 🖥️ Streamlit Web Interface
- 📊 Confidence Score Visualization
- 🧪 Error Level Analysis (ELA)
- 🧩 Edge Detection Analysis
- 📈 RGB Histogram Analysis
- 🧾 Metadata Inspection
- ⚡ Real-time Prediction System

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Streamlit
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Plotly
- Pillow (PIL)
- MediaPipe
- Requests

---

## 📂 Project Structure

```bash
Deepfake-Defender-Pro/
│
├── app.py
├── models/
├── dataset/
├── forensic_analysis/
├── assets/
├── requirements.txt
├── README.md
```

---

## 🧠 Deep Learning Models

### Custom CNN Model
- Convolutional Layers
- Max Pooling
- Batch Normalization
- Dropout Layers
- Dense Layers

### MobileNetV2 Transfer Learning
- Pretrained ImageNet Weights
- Fine-tuning for Deepfake Detection
- Lightweight and Fast Inference

### Ensemble Learning
Predictions from both models are combined to improve overall detection accuracy and reduce classification errors.

---

## 📊 Model Performance

| Metric | CNN Model | MobileNetV2 |
|---|---|---|
| Accuracy | 88.49% | 97.40% |
| Precision | 89.12% | 97.85% |
| Recall | 87.65% | 96.92% |
| F1-Score | 88.38% | 97.38% |
| AUC-ROC | 94.21% | 99.42% |

### Experimental Results

| Run | Accuracy |
|---|---|
| Run 1 | 97.2% |
| Run 2 | 97.5% |
| Run 3 | 97.1% |
| Run 4 | 97.6% |
| Run 5 | 97.4% |

**Mean Accuracy = 97.36% ± 0.18**

---

## 📁 Dataset

The project uses a real-vs-fake facial image dataset divided into:

- Train Dataset
- Validation Dataset
- Test Dataset

### Preprocessing Techniques
- Image Resizing
- RGB Normalization
- Pixel Rescaling
- Dataset Shuffling
- Batch Processing
- Dataset Prefetching

All images were resized to **224 × 224** before training.

---

## ⚙️ How to Run

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Run the Streamlit Application

```bash
streamlit run app.py
```

---

## 📌 System Workflow

1. User uploads image or image URL
2. Face detection using MediaPipe
3. Image preprocessing
4. Prediction using CNN and MobileNetV2
5. Ensemble learning combines predictions
6. Forensic analysis is performed
7. Final result displayed on Streamlit GUI

---

## 🔬 Forensic Analysis Techniques

- Error Level Analysis (ELA)
- Edge Detection
- Metadata Inspection
- RGB Histogram Analysis

---

## 🎯 Future Improvements

- Video Deepfake Detection
- Real-time Webcam Analysis
- Larger Training Datasets
- Transformer-based Models
- Cloud Deployment

---

## 👨‍💻 Authors

- **Rohan Munir**
- **Maryam Khalid**

---

## 📚 References

- TensorFlow
- Streamlit
- OpenCV
- MediaPipe
- MobileNetV2 Research Paper
