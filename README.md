# 👁️✋ Gesture Recognition Virtual Mouse & Keyboard

This project enables users to control their computer using a webcam — with **eye movement controlling the mouse** and **hand gestures controlling keyboard input**. Built using Python, OpenCV, and Haar Cascade Classifiers, this system demonstrates hands-free, AI-powered interaction using computer vision techniques.

---

## 🚀 Features

- 👁️ **Eye Blink Mouse Control**  
  - Single blink → Left Click  
  - Double blink → Double Click  

- ✋ **Hand Gesture Detection**  
  - Move cursor  
  - Simulate keyboard keys  

- 🔐 **User Authentication**  
  - Login & Registration system using Tkinter  
  - Credentials stored securely in SQLite  

- 📸 **Real-Time Webcam Tracking**  
  - Hand, eye, and face detection using Haar Cascade Classifier  

---

## 🛠️ Technologies Used

- **Python 3**
- **Libraries: OpenCV, NumPy, Pillow, pynput, pyautogui**
- **Tkinter (GUI)**
- **SQLite**
- **Haar Cascade Algorithm (from OpenCV)**
- **IDE/Tools: Anaconda, Spyder IDE**


---


## 🧠 How It Works

1. **Login/Register**  
   Users first register or login through a Tkinter-based GUI. Credentials are stored in a local SQLite database.

2. **Gesture Detection**  
   Once logged in, the webcam starts capturing real-time video.

3. **Haar Cascade Detection**  
   Using pre-trained Haar Cascades:
   - Eyes are detected to track blinks
   - Hands are detected to trigger actions

4. **Mouse & Keyboard Simulation**  
   Eye blinks and finger positions are mapped to mouse and keyboard events.

---

---

## 🖥️ Demo

> Coming soon: Demo video or GIF preview of real-time gesture recognition

---

## ✅ Requirements

- Python 3.x
- Anaconda – for environment and package management
- Spyder IDE  – for easier Python GUI development
- OpenCV – pip install opencv-python
- NumPy – pip install numpy
- Pillow – pip install pillow
- pynput – pip install pynput
- pyautogui – pip install pyautogui
- Tkinter – comes built-in with Python
- SQLite3 – built-in with Python

---

## 📌 Setup Instructions


1. Clone the repo:
   
   ```bash
   git clone https://github.com/CodeByGautami/Gesture-Recognition-for-Virtual-Mouse-and-Keyboard.git
   cd Gesture-Recognition-for-Virtual-Mouse-and-Keyboard

2. Install the dependencies:

    ```bash
    opencv-python
    pynput
    tk
    Pillowopencv-python


3. Run the application:

    ```bash
    python gui_master.py

4. Register a New User

    Click on REGISTER → Enter details and capture face data

5. Login and Start Gesture Control

    After registering, click on LOGIN → the gesture control will start once authenticated


## 🧠 How it Works

🖐️ Hand Tracking: 
    Detects hand landmarks using MediaPipe to control the cursor and keyboard.

👁️ Eye Blink Detection:

    Single blink → Single click

    Double blink → Double click

⌨️ Virtual Keyboard: Enables typing using finger gestures.

🔐 Login & Registration: Authenticates users using a local SQLite database.


## 📷 Screenshots

## User Interfaces
<img width="887" height="497" alt="image" src="https://github.com/user-attachments/assets/9880d1c1-9d61-4fb4-bf26-e54b0b5ea166" />
<img width="855" height="481" alt="image" src="https://github.com/user-attachments/assets/8caa2a8e-c88f-4482-aeb3-a81d99c7e092" />

## Login
<img width="865" height="487" alt="image" src="https://github.com/user-attachments/assets/349143cd-edb5-437d-96f0-f8efb5d84820" />

## Output
<img width="816" height="381" alt="image" src="https://github.com/user-attachments/assets/300c7a51-45ad-4c8e-b140-d6a423a7313d" />
<img width="806" height="419" alt="image" src="https://github.com/user-attachments/assets/e2f7810a-f54a-4a3b-9f76-0194b87516ac" />

---

## Recognition or Publication
<img width="889" height="603" alt="image" src="https://github.com/user-attachments/assets/863c8349-faee-4632-937b-6f11ee7f868a" />






