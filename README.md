# Posture Detection Authentication System
The project is mainly focused on facial recognition and posture detection.
An image will be displayed and the user has to mimic the same posture.
The program will detect the posture of the body and hand.
Now the program will create an encoding of the user's face and try to match it with the stored face encoding of the user.

# Installation
`pip install opencv-python==4.5.5.62
pip install face-recognition==1.3.0 #(first install visual studio in the system)
pip install matplotlib==3.1.1 
pip install mediapipe==0.8.9.1 
pip install numpy==1.16.5 
pip install opencv-python==4.5.5.62 `
# Face Encoding.py
`Encode_Images(path):` <br/>
Pass the file location where the photo of the users are stored with a '/' at the end

# Posture Based Authentication System.py
`Verify(Gesture_Image,Selfie_Image)` <br/>
Pass the provided Gesture and the selfie of the user mimicking the user
