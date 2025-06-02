# gesture-volume-control-2024
gesture-volume-control-2024

version Python 3.12.7 
Steps 

Step 1 - create virtual environment
command - python -m venv venv

step 2 - activate venv
command - .\venv\Scripts\activate

step 3 - install requirements
command - pip install -r requirements.txt

step 4 - run app
command - python app.py



📌 PROJECT DESCRIPTION:
A real-time system that uses hand gestures to control the system volume. It detects the distance between the thumb and index finger using a webcam and adjusts volume accordingly.

🔑 KEY FEATURES:

Real-time hand tracking

Gesture-based volume control

Visual feedback using OpenCV

Works with system audio (via pycaw on Windows)

🧠 SYSTEM ARCHITECTURE:

Input: Webcam captures hand gestures.

Processing: MediaPipe detects hand landmarks.

Logic: Calculates distance between fingers.

Action: Maps distance to volume range.

Output: Adjusts system volume and shows feedback on screen.

🛠️ TOOLS USED:

Python – Programming language

OpenCV – Video processing

MediaPipe – Hand detection

NumPy – Distance calculation

pycaw – Volume control on Windows
