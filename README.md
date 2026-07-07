# 🚧 AI-Based Road Pothole Detection System

An intelligent computer vision application that automatically detects potholes, cracks, and manholes from road images and videos using the **YOLOv8 object detection model**. The system analyzes road conditions, estimates damage severity, stores detection records, and generates reports to support road maintenance and smart city infrastructure.

---

## 📌 Features

* 🚗 Detect potholes, cracks, and manholes
* 🎥 Real-time image and video detection
* 🤖 YOLOv8-based object detection
* 📊 Severity analysis of detected road damage
* 🗄️ SQLite database for storing detection history
* 📈 Dashboard for monitoring detections
* 📄 Automatic report generation
* 📷 Save evidence images for detected defects

---

## 🛠️ Technologies Used

* Python
* YOLOv8 (Ultralytics)
* OpenCV
* Flask
* SQLite
* Pandas
* NumPy

---

## 📂 Project Structure

```text
road_pothole_detection/
│
├── alerts/
├── dashboard/
├── database/
├── detection/
├── models/
├── utils/
├── evidence/
├── app.py
├── config.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/road-pothole-detection.git
cd road-pothole-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python app.py
```

The application starts the detection system and dashboard for monitoring road defects.

---

## 🧠 Detection Workflow

```text
Road Image / Video
        │
        ▼
YOLOv8 Detection
        │
        ▼
Road Defect Classification
        │
        ▼
Severity Analysis
        │
        ▼
Database Logging
        │
        ▼
Dashboard & Reports
```

---

## 🎯 Detected Classes

* Pothole
* Crack
* Manhole

---

## 📊 Key Features

* High-speed object detection
* Automatic road damage classification
* Severity estimation
* Evidence image storage
* Detection history
* Report generation

---

## 🔮 Future Improvements

* GPS location tagging
* Google Maps integration
* Mobile application
* Live CCTV support
* Cloud deployment
* Road condition analytics dashboard
* Automatic maintenance alerts

---

## 📚 Applications

* Smart Cities
* Highway Monitoring
* Municipal Road Maintenance
* Infrastructure Inspection
* Transportation Departments

---

## 👨‍💻 Author

**Vinod Kumar Gudiseva**

B.Tech – Artificial Intelligence & Machine Learning

---

⭐ If you found this project useful, consider giving it a star.
