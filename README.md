# poor_man_rekognition
GSOC project 2019

Building a free version of Amazon rekognition with maximum possible feature during a 3 months’ time span.

Use-cases:

   	1.Face and Eye Detection using OpenCV
	2.Facial recognition of a video using deep metric learning
	3.Celebrity Recognition
 	4.Object Detection
	5.Read text in images
 	6.Facial Analysis
 		Sad
 		Happy
 		Angry
 		Disgust
 		Fear
 		Surprise
 		Neutral
 	7.Scene Detection

Libraries required:

	OpenCV: For using cascade files
	Numpy: For array operations
	Matplotlib.pyplot : For plotting
	Pickle : For serializing and de-serializing Python object structures
	Keras : For importing neural network models 
	Tensorflow : For CNN’s architecture and training
	Cython :  To generate CPython extension modules
	Pillow : To load images from files
	Lxml : To use the ElementTree API
	Flask==1.1
	gunicorn==19.3
	werkzeug==0.15
	opencv
	tesseract=3.02
	numpy==1.11
	scipy==0.18
	scikit-learn>=0.18

4 simple steps to download this repo, run in your local server and work on it accordingly.

Step 1.
        Download or clone this repo.

Step 2.
        Get the requirments by typing in the command.
        pip install -r requirements.txt
        
Step 3.
        You are good to go.
        RUN $python app.py
     
Step 4.
        Open http://127.0.0.1:5000/ in your browser
