# Face-Recognition
Face Recognition

**Steps To Perform:**


•	Import required Python libraries
•	Start webcam
•	Read, resize and display the image.
•	Download the pre-trained face detection model, consisting of two files:
•	Load the pre-trained face detection network model from disk
•	Use the dnn.blobFromImage function to construct an input blob by resizing the image to a fixed 300x300 pixels and then normalizing it.
•	Pass the blob through the neural network and obtain the detections and predictions.
•	Loop over the detections and draw boxes around the detected faces
•	Show the resulting image
