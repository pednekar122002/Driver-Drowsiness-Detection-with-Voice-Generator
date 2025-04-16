 Driver Drowsiness Detection with Voice Generator 
 Project Overview
 This Python-based project leverages computer vision and facial landmarks to detect signs of fatigue in a driver 
 and issues a voice warning if drowsiness is detected. It is designed to run with no additional hardware—only a webcam and Python environment are needed.

  Features
  Real-time webcam-based drowsiness monitoring
- Eye Aspect Ratio (EAR) & Mouth Aspect Ratio (MAR) detection
- Voice alert using `pyttsx3` if drowsiness is detected
- Simple web UI (`index.html`, `about.html`) for basic interaction (optional)
- Modular Python files:
  - `app.py` - Entry point or app wrapper
  - `drowsiness_detection.py` - Main detection logic
  - `index.py` - Optional for launching via a web interface
 
  -  Technologies Used
  -  Python 3.x
  - OpenCV
  - dlib (facial landmark detection)
  - imutils
  - NumPy
  - pyttsx3 (text-to-speech)
 
   File Structure
  
  `plaintext
  
├── app.py                   # Entry point (can call detection or UI)
├── drowsiness_detection.py  # Main detection code using EAR & MAR
├── index.py                 # Optional routing or app logic
├── index.html               # Frontend UI page
├── about.html               # Info/about page
├── README.md                # Project documentation
├── requirements.txt         # Dependencies
