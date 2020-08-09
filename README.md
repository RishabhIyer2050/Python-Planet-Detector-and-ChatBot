# About the Project

<p>The project uses a picture as an input and detects which planet it is, using Machine Learning. The Planet Recognition system consists of a pertained ResNet50 Model with its last layer replaced by a softmax unit of 10 units. The model is Built using the Keras library. The weights of the ResNet50 are set to non-trainable while the the weights of the softmax unit are trained using a small image dataset of planets downloaded from google images.</p>
<p>There is also a python chatbot which can crack jokes, greet you etc. We built the GUI using Tkinter library of Python. The ChatBot is built using NLTK which is a Natural Language Toolkit in python. It is a rule based chatbot that replies to simple questions like: ”What is your name?”, “Tell me a joke”, “Tell me a fact”. It is able to reply to simple questions by the user.</p>

# Steps to run the project
<ol>
  <li> Run the "Planet Detector Neural Network.ipynb" file first. This will save a file called "modelnew.h5" in your disk. This file contains the CNN architecture and pre trained weights.</li>
  <li> Now run the "Trained CNN and ChatBot.py" file. This file loads the pre-trained CNN which takes some time and runs the the Planet Detector and ChatBOt in a easy-to-use GUI.</li>
 </ol>
