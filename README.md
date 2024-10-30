# Age-Gender-Detector

This project implements a real-time age and gender detection system using OpenCV and deep learning techniques. The model detects faces in video streams and predicts the age and gender of each detected face using pre-trained models.

## Technologies Used

- Python
- OpenCV
- Deep Learning (Caffe framework)
- Pre-trained models for age and gender detection

## Project Workflow

1. **Setup Environment**
   - Install necessary libraries (OpenCV, NumPy).
   - Download pre-trained models for age and gender detection.

2. **Face Detection**
   - Use OpenCV's `dnn` module to load the face detection model.
   - Capture video stream from the camera or video file.
   - Process each frame to detect faces.

3. **Age and Gender Prediction**
   - For each detected face, extract the face region and preprocess it.
   - Pass the preprocessed face through the age and gender detection models.
   - Retrieve predictions and classify them into age ranges and gender categories.

4. **Display Results**
   - Draw bounding boxes around detected faces.
   - Annotate the age and gender predictions on the video feed.
   - Continuously display the annotated video in real-time.

5. **End the Process**
   - Provide an option to terminate the video stream (e.g., by pressing 'q').
   - Release the video capture and close all windows.

## Usage
-Make sure your camera is working and accessible.
-Run the script to start detecting age and gender in real-time.
-You can press 'q' to exit the application.

##Key Learnings
-Gained hands-on experience with real-time video processing and deep learning.
-Improved understanding of OpenCV and its applications in computer vision.
-Learned how to effectively implement and utilize pre-trained models.

##Feedback
I welcome any feedback or suggestions on the project! Feel free to reach out or contribute to enhance the functionality and accuracy of the model.
