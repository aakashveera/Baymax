# Baymax

<a href='https://en.wikipedia.org/wiki/Baymax'>Baymax</a> is a Fictional Character that takes care about our health.

It is simulated in python using AI techniques such as <b>Face Recognition</b>, <b>Emotion Detection</b>, <b>Chatbot</b> and <b>Speech Recognition</b>. 

## 1) Face Recognition:
  For Face Recognition <a href='https://github.com/ageitgey/face_recognition'>face_recognition</a> library is used.
  
## 2) Emotion Detection:
  For Emotion Detection Convolutional Neural Networks model is used trained on the <a href='https://www.kaggle.com/msambare/fer2013'>FER Dataset</a>
  
## 3) Chatbot:
  Chatbot is created using Dialogflow and the API is used in Python.<br>
  
## 4) Speech Recognition:
  Google Speech Recognition API is used for audio to text conversion and Microsoft Speech API(SAPI) is used for text to audio(male voice).

For Usage,<br>

### Requirements:
Install the following requirements using CMD with pip command.
1. Numpy (pip install numpy)
2. OpenCV (pip install opencv-python)
3. Cmake (pip install cmake) - To use dlib
4. Dlib (pip install dlib)
5. face-recognition (pip install face-recognition) 
6. Speech Recognition (pip install SpeechRecognition)
7. Playsound (pip install playsound)
8. Pywin32 (pip install pywin32)

While installing face-recognition take a look at <a href='https://github.com/ageitgey/face_recognition/issues/175#issue-257710508'>here</a> to solve issues if any.

<br>
Once requirements are installed place the images to be used for face recognition inside the images folder and make the path changes in the necassary places. Also you will need to place the private key(JSON file) to use the dialogflow API inside python.
