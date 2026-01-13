Real-Time Eye Tracking System

A real-time eye tracking system built using OpenCV and MediaPipe Face Mesh that detects and tracks iris movement from a live webcam feed and estimates the user’s gaze direction (Left, Center, Right). This project demonstrates real-time computer vision, facial landmark detection, and gaze estimation suitable for human–computer interaction, AR/VR, and attention-tracking applications.

⸻

🚀 Features
	•	Real-time webcam-based eye tracking
	•	Accurate iris detection using MediaPipe Face Mesh
	•	Gaze direction estimation (Left / Center / Right)
	•	Low-latency performance suitable for live interaction
	•	Works on Windows, macOS, and Linux

⸻

🧠 How It Works

The system uses MediaPipe’s Face Mesh model to detect 468 facial landmarks, including precise iris landmarks.
By computing the relative position of the iris center inside the eye region, the system estimates the user’s gaze direction.

Pipeline:
	1.	Capture video from webcam using OpenCV
	2.	Detect facial landmarks using MediaPipe
	3.	Extract iris coordinates
	4.	Compute gaze ratio
	5.	Display eye position and gaze direction in real time

⸻

📦 Tech Stack
	•	Python
	•	OpenCV
	•	MediaPipe
	•	NumPy
