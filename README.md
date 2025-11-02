# 💤 Driver Drowsiness Detection
---

## 🚗 Overview  
Driver drowsiness is one of the major causes of road accidents worldwide.  
This project aims to **detect and alert drivers** when they show signs of drowsiness in real time using computer vision techniques.  

The system monitors the driver’s eyes through a webcam feed.  
If the eyes remain closed beyond a certain threshold, it triggers an **audio alert** to wake the driver — enhancing road safety and preventing accidents.

---

## 🧠 Features  
- 👁️ **Real-time Eye Detection** using Haar Cascade and Dlib facial landmarks  
- 😴 **Drowsiness Detection Algorithm** based on Eye Aspect Ratio (EAR)  
- 🔊 **Alert System** that triggers a warning sound when drowsiness is detected  
- ⚡ **Lightweight & Real-Time Processing** on standard hardware  

---

## ⚙️ Tech Stack  
- **Language:** Python  
- **Libraries:**  
  - OpenCV — image & video processing  
  - Dlib — facial landmark detection  
  - NumPy — numerical computations  
  - imutils — frame manipulation  
  - playsound — audio alerts  

---

## 📸 How It Works  
1. Capture real-time video feed from the webcam.  
2. Detect the face and eyes using Haar Cascade or Dlib.  
3. Calculate the **Eye Aspect Ratio (EAR)** from facial landmarks.  
4. If EAR < threshold for consecutive frames → **Driver is drowsy**.  
5. Trigger an alarm sound to alert the driver.  

---

## 🚀 Getting Started  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/KaustubhSastry/Driver-drowsiness-detection-system.git
cd driver-drowsiness-detection
