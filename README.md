# 🎯 Face Recognition Based Attendance System

<p align="center">
  <img src="https://raw.githubusercontent.com/opencv/opencv/master/doc/opencv-logo.png" width="180">
</p>

<p align="center">
  <b>Automated Attendance System using Face Recognition and Computer Vision</b>
</p>

---

## 📌 Overview

The **Face Recognition Based Attendance System** is a Python-based desktop application that automates attendance marking using real-time facial recognition technology.

The system captures face images using a webcam, trains a recognition model, and identifies users automatically during attendance logging.

It helps eliminate:
- ❌ Proxy attendance
- ❌ Manual attendance errors
- ❌ Time-consuming attendance processes

---

## 🚀 Features

✅ Face Detection using Haar Cascade Classifier  
✅ Face Recognition using LBPH Algorithm  
✅ Real-Time Attendance Tracking  
✅ Attendance Storage in CSV Format  
✅ GUI using Tkinter  
✅ Password Protected Training System  
✅ Automatic Date & Time Logging  
✅ Student Registration System  

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core Programming |
| OpenCV | Face Detection & Recognition |
| Tkinter | GUI Development |
| NumPy | Numerical Operations |
| Pandas | CSV/Data Handling |
| Pillow | Image Processing |

---

## 📂 Project Structure

```text
FaceRecognitionAttendanceSystem/
│
├── Attendance/
├── StudentDetails/
├── TrainingImage/
├── TrainingImageLabel/
├── haarcascade_frontalface_default.xml
├── main.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/FaceRecognitionAttendanceSystem.git
```

---

### Step 2: Install Requirements

```bash
pip install -r requirements.txt
```

---

### Step 3: Run the Project

```bash
python main.py
```

---

## 📸 How It Works

### 1️⃣ Register User
- Enter ID and Name
- Capture face images using webcam
- Images are stored in `TrainingImage/`

### 2️⃣ Train Model
- Click **Save Profile**
- LBPH recognizer trains the dataset
- Model saved in `TrainingImageLabel/`

### 3️⃣ Mark Attendance
- Click **Take Attendance**
- Webcam detects and recognizes face
- Attendance stored automatically

---

## 📁 Attendance Format

```csv
ID,NAME,DATE,TIME
22803014,Tanmay Butta,17-11-2024,14:11:54
22803006,Sabeeh Ahsan,17-11-2024,14:15:03
```

---

## 🔐 Security Features

- Password protected profile training
- Prevents unauthorized modifications
- Secure attendance handling

---

## 📷 Screenshots

### Main GUI
- User Registration Panel
- Attendance Display Panel

### Face Detection
- Real-time face recognition through webcam

### Attendance Table
- Live attendance updates with timestamp

---

## 🔮 Future Enhancements

- 🔹 MySQL Database Integration
- 🔹 Cloud Attendance Backup
- 🔹 Mobile Application
- 🔹 Deep Learning Face Recognition
- 🔹 Mask Detection
- 🔹 Email Notifications

---

## 👨‍💻 Contributors

- Sabeeh Ahsan
- Tanmay Butta
- Aryan Khanna

---

## 📚 References

- OpenCV Documentation  
  https://docs.opencv.org/

- Python Documentation  
  https://docs.python.org/

- Face Recognition Tutorial  
  https://realpython.com/face-recognition-with-python/

---

## ⭐ Conclusion

The Face Recognition Based Attendance System provides a modern, efficient, and secure method for attendance management using artificial intelligence and computer vision technologies.

It improves accuracy, reduces manual effort, and prevents proxy attendance effectively.

---

<p align="center">
  Made with ❤️ using Python & OpenCV
</p>
