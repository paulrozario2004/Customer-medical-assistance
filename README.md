📌 Project Overview: How It Works
This real-time fall detection system is designed to monitor customers in retail stores and identify if anyone has fallen due to a medical emergency. Using a USB webcam and a Raspberry Pi, the system ensures customer safety by detecting abnormal postures and triggering instant alerts for store staff.

🚀 How It Works:
1️⃣ Capturing Video – A USB webcam continuously records real-time footage of the store area.
2️⃣ Pose Detection – MediaPipe Pose detects key body landmarks from the video stream.
3️⃣ Posture Analysis – The AI model classifies whether a person is standing, sitting, or lying down.
4️⃣ Fall Detection Logic

If a person suddenly transitions to a lying posture and remains down, it's classified as a fall.

An alarm is activated, and a notification is sent to staff immediately.
5️⃣ Real-Time Response – Staff can quickly respond to provide help, potentially preventing serious outcomes.

🎯 Features
✅ AI-based fall detection with pose estimation
✅ Real-time alerts and audible alarm when a fall is detected
✅ Low-cost, efficient solution using Raspberry Pi and USB webcam
✅ Helps staff respond quickly to possible medical emergencies

🛠️ Tech Stack
Hardware: Raspberry Pi, USB Webcam
Software: Python, MediaPipe Pose, OpenCV
Communication: Real-time alerts via audio or connected devices

