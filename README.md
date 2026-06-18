# 🖐️ AI Virtual Mouse using Hand Gestures

Control your computer mouse using hand gestures with the help of **OpenCV**, **MediaPipe**, and **PyAutoGUI**. This project tracks hand landmarks in real-time and performs mouse actions such as moving the cursor, left click, right click, double click, and taking screenshots.

---

## ✨ Features

- 🖱️ Cursor movement using index finger
- 👆 Left click gesture
- 👉 Right click gesture
- 👆👆 Double click gesture
- 📸 Screenshot capture gesture
- 🔍 Real-time hand tracking with MediaPipe
- ⚡ Fast and lightweight

---

## 📷 Demo

<div align="center">

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-green?logo=opencv)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hand_Tracking-orange)
![License](https://img.shields.io/badge/License-MIT-red)

</div>

---

## 🛠️ Tech Stack

- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- Pynput

---

## 📂 Project Structure

```
AI-Virtual-Mouse/
│
├── main.py            # Main application
├── util.py            # Utility functions (distance and angle calculations)
├── requirements.txt
├── screenshots/
├── README.md
└── assets/
```

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/AI-Virtual-Mouse.git
cd AI-Virtual-Mouse
```

### Install dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install opencv-python mediapipe pyautogui pynput numpy
```

---

## ▶️ Run the Project

```bash
python main.py
```

---

## 🎯 Supported Gestures

| Gesture | Action |
|-----------|--------|
| Index finger extended | Move cursor |
| Index finger bent | Left click |
| Middle finger bent | Right click |
| Index + Middle finger bent | Double click |
| Thumb close to index + both bent | Screenshot |

---

## ⚙️ How It Works

1. Captures video from webcam.
2. Detects hand landmarks using MediaPipe.
3. Calculates angles and distances between fingers.
4. Recognizes predefined gestures.
5. Executes mouse events via PyAutoGUI and Pynput.

---

## 📸 Screenshots

When the screenshot gesture is detected, images are automatically saved as:

```
my_screenshot_123.png
my_screenshot_456.png
```

---

## 📦 Dependencies

- OpenCV
- MediaPipe
- PyAutoGUI
- Pynput
- NumPy

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🔮 Future Improvements

- Scroll Up / Scroll Down gestures
- Drag and Drop functionality
- Volume control using hand gestures
- Brightness control
- Multi-hand support
- Gesture customization
- Smoothing for cursor movement

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## ⭐ Show Your Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## 👨‍💻 Author

**Eesha Upasya Mishra**

- GitHub: https://github.com/eesha95

---

## 📄 License

This project is licensed under the MIT License.
