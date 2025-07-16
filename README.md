# 📏 Real-Time Facial Structure Measurement (in CM)

This Python application tracks your face in real-time via webcam and accurately **measures facial features in centimeters** using 3D landmark estimation and a known facial reference.

---

## 🔧 Features

- 🎯 Detects and tracks 468 3D facial landmarks using MediaPipe
- 📏 Calculates facial distances in **centimeters**:
  - Interpupillary (eye-to-eye) distance
  - Nose length
  - Lip width
  - Jaw width
  - Forehead-to-chin height
- ⚡ Smooth performance at 30 FPS
- 🧠 Converts pixel distances to CM using interpupillary scaling (assumes ~6.3 cm average)

---

## 📌 Real-World Applications

- Biometric verification and security systems
- Virtual makeup and try-on tools
- Cosmetic and orthodontic diagnostics
- Healthcare AI systems

---

## 🛠️ Technologies Used

- Python 3.7+
- [MediaPipe Face Mesh](https://google.github.io/mediapipe/solutions/face_mesh.html)
- OpenCV

---

## 📦 Install Dependencies

```bash
pip install opencv-python mediapipe
▶️ Run the Application
python facial_structure_measurements.py
Press Esc to exit the webcam window.

📄 License
This project is licensed under the MIT License.
