# EmotionDetection

Real-Time Emotion Detection Using DeepFace
This repository contains a Python script that captures video from your webcam, detects faces in real-time, and predicts the dominant emotion on each detected face using the DeepFace library.

**Features**
Real-Time Face Detection: Utilizes OpenCV's Haar Cascade classifier to detect faces in real-time.
Emotion Prediction: Uses the DeepFace library to analyze the detected face and predict the dominant emotion.
Real-Time Video Display: Displays the video feed with rectangles drawn around detected faces and the predicted emotion displayed above each face.
Easy to Use: Simply run the script, and the webcam feed with real-time emotion detection will be displayed.
**Requirements**
Python 3.x
Libraries:
opencv-python
numpy
deepface
You can install the required libraries using the following command:
![image](https://github.com/user-attachments/assets/4db8fb40-00a6-4256-8cf7-2575aca8ecd3)

pip install opencv-python numpy deepface
How to Run
Clone the Repository:

![image](https://github.com/user-attachments/assets/8a24dbac-8712-41ac-acc6-3ccfd5aa3888)

git clone https://github.com/yourusername/emotion-detection.git

cd emotion-detection

Run the Script:

![image](https://github.com/user-attachments/assets/ac615f84-d909-4a7e-a1ec-e1f687e3a908)

python emotion_detection.py
The script will open a window showing the video feed from your webcam. Detected faces will have a rectangle drawn around them, and the predicted emotion will be displayed above the face.

**Stopping the Script:**

Press the 'q' key on your keyboard to stop the video feed and close the application.
**How It Works**
The script initializes the webcam and sets the frame width and height.
A pre-trained Haar Cascade model is loaded to detect faces in each video frame.
Once a face is detected, the DeepFace library analyzes the face and predicts the dominant emotion.
The predicted emotion is displayed above the detected face in the video feed.
**Example**
Once the script is running, you will see a live video feed where:

Faces detected by the Haar Cascade model are highlighted with a rectangle.
The dominant emotion for each face is displayed above the corresponding rectangle.
**Troubleshooting**

Camera Not Detected: Ensure that your webcam is properly connected and recognized by your system.

DeepFace Error: If DeepFace cannot analyze the face, check if the face region is well-lit and clearly visible.

**Contributing**

Contributions are welcome! Feel free to open issues or submit pull requests to improve this project.
