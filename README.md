# Facial-Expression-recognition
step 1:
Build and train a CNN model in Keras to recognize seven facial expressions by following the steps provided in Facial_expression_training.ipynb file. 
The data consists of 48x48 pixel grayscale images of faces. <br>The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories <br>(0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).<br><br>
step 2:
Once you have trained, saved, and exported the CNN,create a model class to predict the expressions by loading the model from json file and by loading weights . This is done in model.py file.<br><br>
step 3:
Use OpenCV to automatically detect faces(<b>Facial Recognition</b>)in images by drawing square boxes around them,use Flask to build a web application which performs real-time facial expression recognition on video and image data.This is done in the files camera.py and main.py and templates/index.html files.<br><br>
step 4:
Navigate to the root directory and run the file <b>main.py</b> in cmd using the command <b>python3 main.py</b>.


 

