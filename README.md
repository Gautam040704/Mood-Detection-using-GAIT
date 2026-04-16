# 🧠 Mood Detection using Gait Data

A Machine Learning project that predicts human mood (Happy, Sad, Angry) using gait features derived from sensor data.

---

## 🚀 Overview

This project analyzes gait patterns such as cadence, pressure, and motion signals to classify a person's emotional state. It combines feature engineering with a trained ML model to make accurate predictions.

---

## 📁 Project Structure

```
MOOD-DETECTION/
│── model/
│   ├── feature_columns.pkl
│   ├── mood_model.pkl
│
│── notebooks/
│   ├── training.ipynb
│   ├── feature_engineering.ipynb
│   ├── prediction.ipynb
│
│── src/
│   ├── feature_engineering.py
│   ├── predict.py
│
│── final_mood_dataset.csv
│── run.py
│── requirements.txt
│── README.md
```

---

## ⚙️ Setup

```bash
git clone https://github.com/Gautam040704/mood-detection-using-gait.git
cd mood-detection-using-gait
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python run.py
```

---

## 📊 Output

The model predicts one of the following moods:

* 😊 Happy
* 😢 Sad
* 😠 Angry

---

## 🧪 Features Used

* Cadence (steps/min)
* Foot Pressure (FSR sensors)
* IMU Data (Acceleration & Motion)
* Temporal gait patterns

---

## 🤖 Model Details

* Algorithm: Random Forest / ML Model
* Input: Engineered gait features
* Output: Mood classification
* Pipeline: Preprocessing → Feature Engineering → Prediction

---

## 📓 Notebooks

* `training.ipynb` → Model training
* `feature_engineering.ipynb` → Raw data → features
* `prediction.ipynb` → Model testing

---

## 🔮 Future Improvements

* Deploy as a web app (Streamlit/Flask)
* Real-time sensor integration (IoT)
* Deep Learning models (LSTM/Transformer)
* Improve accuracy with larger datasets

---

## 👨‍💻 Author

**Gautam Shah**
B.Tech Student – VIT Chennai

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
