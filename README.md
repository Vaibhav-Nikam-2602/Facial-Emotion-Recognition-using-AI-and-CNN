# Facial Emotion Recognition using AI and CNN 😄😢😡

This project uses **Artificial Intelligence (AI)** and **Convolutional Neural Networks (CNN)** to recognize human emotions from facial expressions in images. It is trained on the **FER2013 dataset** and supports real-time emotion detection via webcam.

---

## 🔍 Overview

Facial expressions are a vital part of human communication. This AI-powered system automates the process of detecting emotions like:

- Happy 😊
- Sad 😢
- Angry 😠
- Surprise 😲
- Fear 😨
- Disgust 🤢
- Neutral 😐

---

## 🧠 Technologies Used

- Python
- TensorFlow & Keras (for CNN)
- OpenCV (for image capture & preprocessing)
- Streamlit or Flask (for user interface)
- FER2013 Dataset (Kaggle)

---

## ⚙️ How the AI System Works

1. **Data Preprocessing** – Images resized to 48x48, normalized
2. **CNN Model** – Trained on FER2013 to classify 7 emotions
3. **Prediction** – Softmax layer outputs real-time emotion
4. **Live Detection** – Uses webcam to detect and classify faces

---

## 📂 Folder Structure

```
facial-emotion-recognition-cnn/
├── app.py                 # Main app (Streamlit or Flask)
├── fer_model.py           # CNN architecture
├── model/model.h5         # Trained model file
├── dataset/fer2013.csv    # Training dataset
├── templates/index.html   # HTML UI (Flask)
├── static/                # CSS/JS/Images
├── requirements.txt       # Python dependencies
├── README.md              # Project info
├── .gitignore             # Ignored files
└── LICENSE                # License
```

---

## 🚀 Run the Project Locally

### 1. Clone the Repo

```bash
git clone https://github.com/Vaibhav-Nikam-2602/facial-emotion-recognition-cnn.git
cd facial-emotion-recognition-cnn
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the App

For Streamlit:
```bash
streamlit run app.py
```

For Flask:
```bash
python app.py
```

---

## 📊 Results

- ✅ Accuracy: ~70% on validation dataset
- ✅ Real-time emotion detection via webcam
- ✅ Live overlay of detected emotion on video feed

---

## 🔮 Future Enhancements

- Use advanced AI models like **ResNet**, **MobileNet**
- Add **multi-modal input** (voice + face)
- Convert to Android/iOS using **TFLite**
- Apply in AI-based education, smart healthcare, surveillance

---

## 📚 Dataset

[FER2013 – Kaggle](https://www.kaggle.com/datasets/msambare/fer2013)

---

## 🙋‍♂️ Author

**Vaibhav Nikam**  
📧 vaibhavnikam312@gmail.com

---

## ⚖️ License

This project is licensed under the [MIT License](LICENSE).