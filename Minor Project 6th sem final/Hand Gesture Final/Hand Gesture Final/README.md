

# Game-Automation-Demo
![me](https://github.com/shashankanand13monu/Game-Automation/blob/master/gta_game_demo.gif)
<!-- <img src = "https://github.com/shashankanand13monu/Game-Automation/blob/master/gta_game_demo.gif"> -->
# Game-Automation-WebApp
This is a Demo of Game Automation
## 🔗 Demo Links
[![Streamlit Cloud](https://img.shields.io/badge/Streamlit-Demo-red?style=for-the-badge&)](https://share.streamlit.io/shashankanand13monu/game-automation-webapp/st2.py)
[![Streamlit Cloud](https://img.shields.io/badge/Hugging%20Face-Demo-yellow?style=for-the-badge&)](https://huggingface.co/spaces/shashankanand13/game-automation-webapp)

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

# Advanced
### Add of Remove comment from following code to get Hand Sign Prediction on screen
```python
from tensorflow.keras.models import load_model
model = load_model('mp_hand_gesture')
   # Predict gesture in Hand Gesture Recognition project
                     prediction = model.predict([lmList2forModel])
                     print(prediction)
                     classID = np.argmax(prediction)
                     className = classNames[classID]
                     # show the prediction on the frame
                     cv2.putText(image, className, (10, 50), cv2.FONT_HERSHEY_SIMPLEX,
                                 1, (0,0,255), 2, cv2.LINE_AA)
```
<img src="https://i.imgur.com/hcCnLIn.png">
