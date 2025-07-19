# Automated-Weapon-Detection
## 📌 Project Overview

This repository contains a real-time **Automated Weapon Detection System** using **YOLOv8** (You Only Look Once) for object detection on images and video streams. The system accurately identifies and classifies various types of weapons and is designed to support security and surveillance applications. With a user-friendly PyQt5 interface, it allows seamless control over detection, visualization, and alert settings.

---

## 🧠 Features

- 🔍 Real-time object detection using YOLOv8
- 🖥️ GUI built with PyQt5 for user-friendly interaction
- 📸 Automatic saving of frames with detected weapons
- 🛠️ Custom settings through a dedicated configuration window
- 🔐 Secure login system
- 📋 Object labels managed via `obj.names`

---

## 🗂️ Project Structure
├── UI/ # GUI assets (icons, styles, etc.)
├── cfg/ # Config files (e.g., thresholds, user data)
├── saved_frame/ # Saved screenshots with detections
├── weights/ # YOLOv8 trained weights (.pt file)
├── pycache/ # Auto-generated Python cache files
├── detection.py # Core detection logic using YOLOv8
├── detection_window.py # GUI window for live detection
├── login_window.py # User login interface
├── main.py # Entry point to launch the app
├── settings_window.py # GUI for configuring settings
├── obj.names # List of class labels (e.g., pistol, knife)
├── tempCodeRunnerFile.py # Temporary dev file (can be ignored)
├── requirements.txt # Python dependencies
├── .gitignore # Git ignore rules
└── README.md # Project documentation


---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Automated-Weapon-Detection.git
cd Automated-Weapon-Detection
```
---

### 2. Create a virtual environment (optional)

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

---

### 3. Install dependencies
pip install -r requirements.txt

---
### 4. Download and add your YOLOv8 model
Place your trained YOLOv8 .pt file (e.g., best.pt) into the weights/ folder.

## 🧩 Requirements
Python 3.8+

Ultralytics YOLOv8

PyQt5

OpenCV

NumPy

Pillow

---

## 🧠 Notes
obj.names: Contains object class names (e.g., pistol, knife) – one per line.

weights/: Should include your .pt model file trained with YOLOv8.

cfg/: Optional folder for detection thresholds, user credentials, and other settings.

saved_frame/: Detected frames will be automatically saved here.

---

## 📸 Example Output

