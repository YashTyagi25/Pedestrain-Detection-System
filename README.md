# Pedestrain-Detection-System
The Pedestrian Detection System is an advanced computer vision project aimed at enhancing road safety by accurately identifying and tracking pedestrians in real-time. 
Leveraging state-of-the-art techniques in image processing and machine learning, this system provides an effective solution for detecting pedestrians in various environmental conditions, including crowded urban streets and low-light scenarios.

  Key Components:

   1.Image Acquisition and Preprocessing
   
   2.Feature Extraction
   
   3.Machine Learning Model
   
   4.Object Detection
   
   5.Bounding Box Localization
   
   6.Tracking and Velocity Estimation
   
   7.Integration with Vehicle Systems
   
   8.Performance Evaluation


1. Tech Stack Used:
   - OpenCV: Utilized for image processing tasks such as reading, resizing, and drawing rectangles around detected pedestrians.
   - imutils: Used for convenient image resizing while maintaining aspect ratio, enhancing the efficiency of pedestrian detection.

2. How it is Used:
   - **OpenCV**: 
     - Reads the image from the specified file path using `cv2.imread()`.
     - Resizes the image using `imutils.resize()` to ensure it fits within a maximum width of 400 pixels while maintaining the aspect ratio.
     - Detects pedestrians in the resized image using the Histogram of Oriented Gradients (HOG) method with `hog.detectMultiScale()`.
     - Draws rectangles around the detected pedestrians using `cv2.rectangle()`.
     - Displays the output image with rectangles drawn around pedestrians using `cv2.imshow()` and waits for a key press to close the window.
   - **imutils**:
     - Provides the `resize()` function to conveniently resize images while maintaining their aspect ratio, improving the speed and accuracy of pedestrian detection.

