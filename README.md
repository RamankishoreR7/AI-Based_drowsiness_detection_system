# AI-Based_drowsiness_detection_system
This project focuses on detecting driver drowsiness in real time using a webcam. The idea came from a simple but serious problem — many road accidents happen because drivers feel sleepy and lose attention.

To tackle this, I built a system that continuously monitors eye activity and triggers an alert when signs of drowsiness are detected.

🚀 What it does
Tracks eye movement using a webcam
Detects when eyes remain closed for too long
Sends an alert to warn the user
Works in real time with smooth performance
🛠️ Tech Stack
Python
OpenCV
NumPy
(TensorFlow – if you used it)
🧠 How it works (in simple terms)

The system captures live video and focuses on the eye region.
It calculates something called the Eye Aspect Ratio (EAR) to understand whether the eyes are open or closed.

If the eyes stay closed beyond a certain threshold, it assumes the person is drowsy and triggers an alert.

📂 Project Structure
drowsiness-detection/
│── main.py
│── utils/
│── requirements.txt
│── README.md
⚙️ How to run this project
Clone the repository
git clone https://github.com/YOUR_USERNAME/drowsiness-detection.git
cd drowsiness-detection
Install dependencies
pip install -r requirements.txt
Run the program
python main.py
📊 Output
Detects eye closure in real time
Triggers alert when drowsiness is detected
Runs smoothly on a standard webcam setup
🔮 What I’d like to improve next
Improve accuracy using deep learning models
Build a simple UI for better usability
Try deploying it as a web app
Add support for mobile devices
👨‍💻 About Me

I’m currently learning AI/ML and building projects to understand how these systems work in real-world scenarios.

Raman Kishore R
🔗 LinkedIn: https://www.linkedin.com/in/ramankishore-ravi-664a83379
💻 GitHub: https://github.com/RamankishoreR7
