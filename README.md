# -Music-Recommender-System-based-on-Emotions
This a ml project. Music Recommender System based on Emotions


About the project:

The traditional method of recommending songs is based on learning a user's preferences over time, including past song choices, and listening habits. However, developers have proposed a new approach to song recommendation that uses a person's picture to determine their mood. Using this information, song recommendations are made that best suit the predicted mood.

To recommend songs based on a user's mood, the algorithm follows two main steps. First, the user's input image is processed using OpenCV, a Python library for computer vision, and fed into a convolutional neural network (CNN) in conjunction with a deep neural network (DNN) to predict the user's mood as either 'Happy' or 'Sad'. Next, unsupervised machine learning techniques are used to cluster songs into two classes: 'VERY ENTERTAINING' (class 0) and 'RELAXED' (class 1) using the K-means algorithm. Based on the user's predicted mood, the algorithm recommends songs in order of their current popularity, selecting 'VERY ENTERTAINING' songs to cheer up a sad user and 'RELAXED' songs for a happy user. The neural network can be customized by modifying the code in the 'Emotion_detector_version2' iPython notebook, and the final model is saved as 'final_model.h5'. This approach offers a unique approach to song recommendation, departing from the common practice of recommending sad songs for users in a bad mood.

The data that developers have used here is from https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks
This file contains more than 160,000 songs collected from Spotify Web API, and you can find data grouped by artist, year, or genre in the data section.
It has features like acoustic Ness, energy, loudness and danceability which make the clustering algorithm work more effectively.


Libraries used:
OpenCV.
Tensorflow and Keras.
Sklearn.
LightGBM.
Spotipy.
Tkinter.
Pillow.

How to use:

To use this application, simply execute the run.py file, which will prompt the user to enter the name of the artist they are interested in. The application will then gather the necessary albums from the API and activate your webcam. Press the 'q' button on your keyboard to stop capturing the image and follow the prompts provided by the GUI. Once completed, clicking the print button will generate song recommendations for you. We can enjoy using this unique and engaging application!

Idea behind the project –

The human face can provide important cues about an individual's mood, which can be extracted directly using a camera. One application of this input is to deduce a person's mood, which can be used to generate a list of songs that align with their emotional state. This process eliminates the need for manual song segregation, making it easier to create appropriate playlists based on a person's emotional features. The Facial Expression Based Music Player aims to scan and interpret this data, creating a playlist based on the provided parameters. Our proposed system focuses on detecting human emotions to develop an emotion-based music player. We will explore the approaches used by existing music players to detect emotions and discuss how our system is better equipped for emotion detection.


Functionalities –

1. Face Detection and Facial Expression Recognition System

2. Emotional Recognition from Facial Expression Analysis using Bezier Curve Fitting 

3. Using Animated Mood Pictures in Music Recommendation 

4. Human-computer interaction using emotion recognition from facial expression

5. Emotion-based Music Recommendation By Association Discovery from Film Music

6. Mood Play: Interactive Mood-based Music Discovery and Recommendation


Observations –


The Facial Expression Based Music Player is a system that uses the human face to detect an individual's mood through a camera. The input obtained from the camera is used to deduce the individual's emotion, which is then used to generate an appropriate playlist based on their emotional features. 

This eliminates the tedious task of manually grouping songs into different lists. The system focuses on detecting human emotions for developing an emotion-based music player. This project analysed the approaches used by available music players to detect emotions and proposes a better approach for emotion detection. We used PyCharm tool for the analysis.

 The project outcome is split into two phases: the first phase involves developing software to recognize user emotions based on facial expressions using Python, and the second phase involves integrating the Python code into the web service to play music based on the facial expression.
