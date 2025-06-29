
# 🚨 Alert System for Enhanced Safety Using ML-Based Fatigue Monitoring

**📅 Duration:** March 2025 – June 2025   
**👩‍💻 Developed by:** Mareddy Akhila

---

## 🧠 Project Overview

This project focuses on building a **real-time fatigue detection system** to enhance safety, particularly in high-risk environments like driving or industrial operations. By integrating **physiological**, **visual**, and **behavioral** data, and applying machine learning and deep learning techniques, the system aims to detect early signs of fatigue and trigger timely alerts — potentially saving lives.

---

## 🎯 Key Features

- ✅ Real-time monitoring of driver/user fatigue
- ✅ Multimodal input:
  - **Eye-tracking** (blink rate, EAR, eye closure)
  - **Heart rate variability** (physiological signals)
  - **Keyboard/mouse activity patterns**
- ✅ Advanced ML/DL models:
  - **Convolutional Neural Networks (CNN)**
  - **Long Short-Term Memory (LSTM)**
- ✅ Low-latency alert generation
- ✅ Targeted for deployment on **edge devices**
- ✅ Planned integration with **IoT safety systems**

---

## 🧪 Technologies Used

| Category           | Tools/Technologies                                   |
|--------------------|------------------------------------------------------|
| **Languages**       | Python                                               |
| **ML/DL Models**    | CNN, LSTM                                            |
| **Libraries**       | TensorFlow/Keras, OpenCV, dlib, NumPy, scikit-learn |
| **Data Sources**    | Webcam (visual), Pulse sensor (physiological), Input logs |
| **Target Platform** | Raspberry Pi, Jetson Nano, or other edge devices    |
| **Alert Methods**   | Sound, Vibration, IoT integration                    |

---

## 📂 Project Structure (Planned)

```

FatigueAlertSystem/
│
├── src/                    # Core detection code
│   ├── models/             # CNN/LSTM models
│   ├── processing/         # Feature extraction logic
│   ├── sensors/            # Data acquisition modules
│
├── static/                 # UI assets
├── templates/              # Frontend templates (Flask or Streamlit)
├── logs/                   # Detection logs
├── app.py                  # Main application
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies

```

---

## 📈 Objectives

- Detect fatigue **before critical thresholds**
- Issue alerts to improve driver/operator response time
- Run efficiently on **low-power edge devices**
- Support **offline operation** and **IoT-based integrations**

---

## 🔄 Future Enhancements

- Integrate facial landmark tracking using MediaPipe
- Add support for mobile app notifications via IoT
- Train models using larger real-world datasets
- Apply federated learning for edge-based privacy

---

## 🙋‍♀️ Author

**Mareddy Akhila**  
[GitHub](https://github.com/MareddyAkhila)

---

## 📄 License

This project will be licensed under the MIT License upon release.
