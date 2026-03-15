This project is an AI-based Fire Detection System developed using Python, OpenCV, and YOLOv8. The system analyzes video footage in real time and detects fire using two different methods to improve reliability. The first method uses a trained YOLOv8 deep learning model to identify fire objects in the video frame. The second method uses HSV color segmentation to detect flame-like colors such as bright orange, yellow, and red. By combining these two techniques, the system reduces false positives and improves detection accuracy.

The program processes video frames continuously and displays detection results through a graphical interface built with OpenCV. When fire is detected, the system highlights the region with bounding boxes and displays a warning alert on the screen. A confidence score is also shown to indicate how certain the model is about the detection.

The interface includes features similar to a video player, such as a progress bar, play/pause control, timestamps, and frame rate display. This makes it easier to monitor and analyze detection results while the video is running.

Such a system can be useful in surveillance applications, industrial safety monitoring, forest fire detection, and smart security systems where early fire detection is important for preventing damage and improving response time.
