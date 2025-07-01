#Virtual Mouse using Hand Gestures 🖱️✋

This project allows users to control their computer mouse with hand gestures detected in real time using OpenCV and MediaPipe. It enables full touchless interaction including cursor movement, clicks, screenshots, volume control, and scrolling.

 Features
- Move cursor with index finger
- Left & right click via finger gestures
- Double click
- Take screenshot
- Close window with fist
- Volume control with left hand fingers
- Scroll up/down with hand gestures
- Visual feedback: volume bar & cursor indicators

 Technologies Used
- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- NumPy
- ScreenInfo

  How it Works
- MediaPipe detects hand landmarks
- Logic calculates finger positions/distances
- PyAutoGUI triggers mouse/keyboard actions
- Visual overlays help with interaction

