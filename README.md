# Face_Detection

#It initializes a video capture object to access the webcam (cv2.VideoCapture(0)).

#Inside a loop, it continuously captures frames from the webcam.

For each captured frame:

# It converts the frame to grayscale using cv2.cvtColor.
# It detects faces in the grayscale frame using the detectMultiScale method of the Haar Cascade classifier.
# It draws rectangles around the detected faces using cv2.rectangle.
# It displays the frame with detected faces using cv2.imshow.
# The loop continues until the user presses the 'Esc' key (ASCII code 27).

# Finally, it releases the video capture object and closes all OpenCV windows.

# In summary, the code continuously captures video from the webcam, detects faces in real-time, draws rectangles around the detected faces, and displays the video feed with the detected faces. It allows you to perform real-time face detection using a webcam.