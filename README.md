# virtual-mouse
A Python application for controlling a virtual mouse via hand gestures using OpenCV and MediaPipe. It tracks hand movements to enable cursor navigation, clicking, and scrolling, offering a touchless interface for system interaction.
Key Features:
Hand Gesture Recognition: Utilizes MediaPipe for detecting hand landmarks and interpreting gestures.
Cursor Movement: Move the mouse pointer based on hand movements.
Mouse Clicks: Perform left and right clicks using hand gestures.
Scrolling: Scroll vertically and horizontally with pinch gestures.
Multi-Gesture Support: Includes gestures like fist, index finger, palm, pinch-to-zoom, etc.
Real-time Performance: Optimized for smooth gesture recognition and minimal latency.

#Technologies Used:
Python
OpenCV
MediaPipe
PyAutoGUI for mouse control
NumPy

Installation:
Clone the repository:
git clone https://github.com/yourusername/virtual-mouse-gesture-control.git

Install the required dependencies:
pip install -r requirements.txt

Run the main Python script:
python virtual_mouse.py

#How It Works:
The system captures webcam feed and processes the frames to detect hand landmarks.
Based on the detected gestures, it maps them to corresponding mouse actions like moving the cursor, clicking, and scrolling.
Gestures such as "fist" simulate a mouse press, "index" simulates a right-click, and pinch gestures control scrolling.
The system uses the PyAutoGUI library to simulate mouse actions in real-time.
