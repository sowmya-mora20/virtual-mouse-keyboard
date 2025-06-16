# ✋ Virtual Keyboard & Mouse using Hand Gestures

This project uses **Computer Vision** and **Hand Gesture Recognition** to control a virtual keyboard and mouse, providing a touch-free interface for interaction.

## 🧠 Project Overview

This system allows users to:
- Move and click the mouse using hand gestures
- Type using a gesture-based virtual keyboard displayed on screen

It is especially useful for accessibility applications and touchless environments.

---

## 🧰 Technologies Used

- **Python**
- **OpenCV**
- **MediaPipe**
- **PyAutoGUI**
- **NumPy**
- **Imutils**
- **Pynput**
- **wxPython**

---

## 📁 Files in This Repository

- `virtual_mouse.py`: Controls mouse pointer using hand gestures.
- `virtual_keyboard.py`: Displays an on-screen keyboard and types based on hand gesture detection.

---
## ▶️ How to Run the Project

### 🔧 Prerequisites

Install the required libraries:

```bash
pip install opencv-python numpy imutils pyautogui pynput wxPython
Make sure your webcam is connected and working.

🖱 Run the Mouse Controller
bash
python virtual_mouse.py

⌨️ Run the Virtual Keyboard
bash
python virtual_keyboard.py

Demo : https://www.youtube.com/watch?v=f2_GxtW-_0U&feature=youtu.be
