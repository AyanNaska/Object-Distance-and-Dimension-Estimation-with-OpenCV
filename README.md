# Object-Distance-and-Dimension-Estimation-with-OpenCV
This Python script uses OpenCV for object detection, distance measurement, and dimension estimation. The program calculates the distance and dimensions of objects in the video feed.

## Requirements
- Python 3.x
- OpenCV
- NumPy
- SciPy
- imutils

## Explanation
The script captures video from the default camera (cv2.VideoCapture(0)).
Object detection is performed using contour analysis and morphological operations.
The script calculates the distance and dimensions of the detected object based on a predefined focal length and object width.
The results are displayed on the video feed.

## Parameters
focal_length: The focal length of the camera.
object_width: The known width of the object in centimeters.

## Demo
