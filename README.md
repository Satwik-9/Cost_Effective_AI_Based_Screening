# Cost Effective AI Based Screening

Introduction

This project implements a real-time mask detection system using image processing, deep learning, and OpenCV. It can be used to detect faces in a video stream and predict whether each person is wearing a mask or not.

Dependencies

This project requires the following Python libraries:

OpenCV (cv2)
NumPy (np)
TensorFlow (tf)
scikit-learn (optional, for evaluation metrics)
matplotlib (optional, for plotting)

Download the pre-trained face detection model:

Download the pre-trained face detection model (res10_300x300_ssd_iter_140000.caffemodel) and its corresponding prototxt file (deploy.prototxt) from a reliable source like https://github.com/BVLC/caffe/blob/master/docs/model_zoo.md. Place them in a folder named Face_Detector.
Train your own mask detection model (Optional):

Make sure you have a trained mask detection model saved as mask_detector.keras in the same directory as this script.
Open a terminal or command prompt and navigate to the directory containing this script (e.g., cd mask_detection_project).
Run the script using Python:

Using the webcam:
The script will automatically use your default webcam to capture video.
Faces will be detected in the video stream, and a bounding box with a label ("Mask" or "No Mask") will be drawn for each face along with the predicted probability.
Press the 'q' key to quit the program.
