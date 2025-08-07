Classroom-Activity-Detection
---
A real-time object detection system using YOLOv8 to identify classroom activities like writing, listening, and mobile usage. Built with Python, OpenCV, and Roboflow, and deployable web app for live video monitoring.
---

## 📸 Features

- 🎯 Real-time activity detection using **YOLOv8**
- 🎥 Live webcam feed integration via **OpenCV**
- 🌐 Lightweight **Flask app** for web-based deployment
- 🧠 Detects:
  - Writing ✍️
  - Listening 🎧
  - Using mobile phones 📱
- 🛠️ Easy to modify or extend for additional classroom behaviors

---

## 📁 Project Structure

```
Classroom-Activity-Detection/
│
├── app.py                  # Flask app to serve webcam feed
├── detect.py               # YOLOv8 detection logic
├── utils.py                # Helper functions (if any)
├── templates/
│   └── index.html          # Frontend interface
├── static/
│   └── (optional assets)   # CSS, JS, etc.
├── yolov8-weights/
│   └── best.pt             # Trained YOLOv8 model weights
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## 🔧 Installation

### 🔹 1. Clone the Repository

```bash
git clone https://github.com/alwinsanjo007/Classroom-Activity-Detection.git
cd Classroom-Activity-Detection
```

### 🔹 2. Set Up a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 🔹 3. Install Dependencies

```bash
pip install -r requirements.txt
```

> Ensure you have **Python 3.7+** and **YOLOv8** compatible packages.
---

## 📦 Model Details

- YOLOv8 custom-trained model (`best.pt`) using Roboflow.
- Object classes: `writing`, `listening`, `mobile_usage`
- You can retrain or modify the model using your own dataset via Roboflow or Ultralytics.

---

## 🧪 Sample Use Cases

- Online proctoring
- Classroom behavior analysis
- Lecture attendance & engagement tracking
- AI-assisted classroom monitoring tools

---

## 🛠️ Built With

- [Python](https://www.python.org/)
- [YOLOv8](https://docs.ultralytics.com/)
- [OpenCV](https://opencv.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Roboflow](https://roboflow.com/)

---

## 📌 To-Do / Future Work

- [ ] Add alert system for mobile usage
- [ ] Dashboard for logging student behavior
- [ ] Add more classes (e.g., sleeping, talking)
- [ ] Improve detection accuracy with larger dataset

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Alwin Sanjo**  
GitHub: [@alwinsanjo007](https://github.com/alwinsanjo007)

---
