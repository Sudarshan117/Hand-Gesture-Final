

# Game-Automation-Demo
![me](https://github.com/shashankanand13monu/Game-Automation/blob/master/gta_game_demo.gif)
<!-- <img src = "https://github.com/shashankanand13monu/Game-Automation/blob/master/gta_game_demo.gif"> -->
# Game-Automation-WebApp
This is a Demo of Game Automation
## 🔗 Demo Links
[![Streamlit Cloud](https://img.shields.io/badge/Streamlit-Demo-red?style=for-the-badge&)](https://share.streamlit.io/shashankanand13monu/game-automation-webapp/st2.py)
[![Streamlit Cloud](https://img.shields.io/badge/Hugging%20Face-Demo-yellow?style=for-the-badge&)](https://huggingface.co/spaces/shashankanand13/game-automation-webapp)

## **Hand Gesture–Based Game Automation**

This project demonstrates game automation using real-time hand gesture recognition. By combining computer vision, gesture tracking, and key mapping, it allows you to control a game (like GTA V) using your hands instead of a keyboard or controller.

**📌 Features**

Real-time hand tracking using a webcam.

Gesture-to-action mapping (e.g., ✊ fist = brake, ✋ open palm = accelerate).

Seamless integration with PC games via automated key presses.

Configurable controls – map gestures to any game action.

WebApp Demo showcasing live gesture input, FPS, and key events.

**🛠️ Tech Stack**

Python 3.8+

OpenCV – video capture & image processing

Mediapipe – real-time hand tracking

PyAutoGUI / PyDirectInput – simulate keyboard inputs

Flask / Streamlit (optional) – for web-based visualization
# How To Run
**Creating Running Environment**
```
pip install mediapipe
pip install opencv-python
```
**Optional**
```
pip install pydirectinput
pip install tensorflow
pip install numpy
```
- Run Your IDE as Administrator
- Run The window in which you want to perform opearation
- Run the Code

                     cv2.putText(image, className, (10, 50), cv2.FONT_HERSHEY_SIMPLEX,
                                 1, (0,0,255), 2, cv2.LINE_AA)
```
<img src="https://i.imgur.com/hcCnLIn.png">
