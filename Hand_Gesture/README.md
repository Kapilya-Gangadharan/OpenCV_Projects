# Hand_Gesture_Projects

# Hand Landmark

The hand landmarker model bundle contains a palm detection model and a hand landmarks detection model. The Palm detection model locates hands within the input image, and the hand landmarks detection model identifies specific hand landmarks on the cropped hand image defined by the palm detection model.


<img width="1073" alt="hand-landmarks" src="https://github.com/Kapilya-Gangadharan/OpenCv_projects/assets/105882639/05235267-1a99-4c8b-8ac3-8e923463972b">




Since running the palm detection model is time consuming, when in video or live stream running mode, Hand Landmarker uses the bounding box defined by the hand landmarks model in one frame to localize the region of hands for subsequent frames. Hand Landmarker only re-triggers the palm detection model if the hand landmarks model no longer identifies the presence of hands or fails to track the hands within the frame. This reduces the number of times Hand Landmarker tiggers the palm detection model

# Finger_Count_and_Hand_Detection



# MediaPipe:
MediaPipe is a suite of cross-platform, customizable ML solutions for live and streaming media. One of the provided solutions is an high-fidelity hand and finger tracking. Mediapipe hands tracking can be configured through this app UI through the following params:
Max number of hands to track: Mediapipe can track up to 4 hands in a single image or frame. Default for this app is set to 2.
Minimum detection confidence. Default is set to 50%.
Show/Hide Mediapipe classification results (index, score and label in JSON format). Default is set to False.

# Streamlit:
Streamlit is an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science.The Streamlit web app allows hands tracking in static image  video and live hands-tracking.


# Run the code on command line :

streamlit run Finger_Count_With_Hand_Detection.py
