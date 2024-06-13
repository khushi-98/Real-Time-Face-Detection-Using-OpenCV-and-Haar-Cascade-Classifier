# Real-Time-Face-Detection-Using-OpenCV-and-Haar-Cascade-Classifier

1.Loading the Haar Cascade Classifier:

The classifier is loaded from an XML file (haarcascade_frontalface_default.xml) which contains pre-trained data for detecting frontal faces.

2.Capturing Live Video:

The video feed is captured using OpenCV's VideoCapture method, which interfaces with the default webcam.

3.Processing Frames:

Each frame of the video is converted to grayscale to optimize the performance of the face detection algorithm.
The detectMultiScale method is employed to detect faces in the frame, with parameters fine-tuned for accurate detection.

4.Drawing Bounding Boxes:

For each detected face, a rectangle is drawn around it on the original video frame to visually highlight the face.

5.Displaying the Output:

The processed video frames, with bounding boxes around detected faces, are displayed in a window titled "video_live".
The system continuously updates the video feed until the user presses the 'q' key, which stops the video capture and closes the display window.
