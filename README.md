🧘 YogaCare AI – AI-Powered Yoga Posture Detection

An intelligent and interactive yoga posture detection application built using Python, YOLOv8-Pose, OpenCV, and Streamlit.

Analyze yoga postures in real time, receive posture correction suggestions, calculate joint angles, and get voice feedback to improve your yoga practice.

✨ Features

- 📷 Real-time body pose detection using YOLOv8-Pose.
- 🧘 Analyzes six yoga poses: Warrior II, Tree Pose, Downward-Facing Dog, Plank, Cobra, and Mountain Pose.
- 📐 Calculates joint angles to evaluate body alignment.
- 🎯 Provides posture scores and alignment feedback.
- 🎙️ Offers voice feedback using text-to-speech.
- ⏱️ Tracks posture hold duration.
- 🖥️ Interactive web interface built with Streamlit.
- 🔄 Supports MediaPipe as an alternative pose detection backend.

🛠️ Technologies Used

- Python
- YOLOv8-Pose (Ultralytics)
- OpenCV
- NumPy
- Streamlit
- MediaPipe
- pyttsx3 (Text-to-Speech)
- PyTorch

📦 Installation

1. Install the required libraries:
   
   pip install -r requirements.txt

2. Ensure the required pose detection model files are available in the configured "models/" directory.

🚀 How to Run

Run the following command in your terminal:

streamlit run app.py

The application will start, and Streamlit will provide a local URL to open in your browser.

📖 How to Use

1. Install the required dependencies.
2. Launch the application.
3. Allow camera access if prompted.
4. Select or start a yoga posture analysis session.
5. Perform the yoga pose in front of your camera.
6. View posture analysis, joint-angle information, and alignment feedback.
7. Follow the voice guidance to improve your posture.

Note: Available options may depend on the application's current interface and configuration.

⚠️ Requirements

- Python installed on your system.
- A working webcam or camera.
- Browser or system camera permissions.
- Required Python packages installed.
- Compatible pose detection model files in the expected location.
- A microphone is not required for basic camera-based pose detection; voice feedback uses text-to-speech.

🔮 Future Improvements

- Add support for more yoga poses.
- Improve posture detection accuracy and feedback.
- Add personalized yoga routines based on user progress.
- Include workout history and progress tracking.
- Develop a mobile-friendly interface.
- Add multilingual voice guidance.

👨‍💻 Author

Developed as an AI and computer vision project to explore real-time human pose estimation, yoga posture analysis, and interactive fitness assistance.

📜 License

This project is available for educational and learning purposes. 
