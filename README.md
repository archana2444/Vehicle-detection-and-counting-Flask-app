# Vehicle-detection-and-counting-Flask-app
Developed a Flask-based vehicle detection and counting web application using OpenCV and deep learning. The system detects and tracks vehicles from video streams to provide accurate real-time counts, suitable for traffic monitoring, smart city applications, and congestion analysis.
Built a Vehicle Detection and Counting Web Application using Flask, OpenCV, and a deep-learning object detection model (e.g., YOLO) to automatically detect and count vehicles from video streams. This system can process real-time live camera feeds or uploaded videos, identify vehicles in each frame, and visually display bounding boxes with counts through a web interface.

The backend uses a pre-trained object detection model to locate vehicles (cars, trucks, buses, bikes, etc.) in every frame and tracks their movement to avoid double counting. The video is streamed to the browser using Flask’s streaming response, allowing seamless visualization of real-time detection and counting results.

The application is suitable for traffic monitoring, smart city analytics, congestion analysis, and automated vehicle counting tasks.

Key Features
✔ Detects vehicles in video streams using deep learning models (e.g., YOLO)
✔ Displays real-time vehicle counts on the web interface
✔ Supports live camera feed or pre-recorded video uploads
✔ Tracks vehicles across frames to ensure accurate counts
✔ Built with lightweight Flask backend and OpenCV for efficient processing
