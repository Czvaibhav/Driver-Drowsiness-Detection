# Driver-Drowsiness-Detection
driver-drowsiness-detection/
├── drowsiness_detection.py
├── models/
│   └── shape_predictor_68_face_landmarks.dat
├── sounds/
│   └── 1.mp3
└── README.md

 
    - 
**drowsiness_detection.py:** This is the main Python script that contains the drowsiness detection algorithm. It captures video from the webcam, analyzes eye aspect ratios, detects drowsiness, and displays alerts.

**models/:** This directory holds the pre-trained shape predictor model (shape_predictor_68_face_landmarks.dat) that's used by dlib for facial landmark detection.

**sounds/:** This directory contains the alert sound file (1.mp3) that is played when the driver is detected as drowsy.

**README.md:** A Markdown file providing a brief overview of the project, how to set it up, and how to run the drowsiness detection script.

# Explanation:

**drowsiness_detection.py:** This is where your main code resides. You would commit and push this file to your Git repository. This is the heart of your project that implements the driver drowsiness detection.

**models/:** The pre-trained shape predictor model (shape_predictor_68_face_landmarks.dat) is a crucial component for facial landmark detection. It's a binary file and should be part of your repository if it's not too large.

**sounds/:** This directory contains the audio alert that's played when the driver is detected as drowsy. You would include this directory if you want to share the sound with others who might clone your repository.

**README.md:** A README file helps users understand your project quickly. It can include installation instructions, dependencies, usage instructions, and other project-related details. It's a good practice to include one in your repository.

# Video Input:
The code doesn't directly handle video input in the provided script. However, you can modify the script to read from a video file or a live webcam feed by using OpenCV's VideoCapture class. If you plan to work with video files, you might create an additional folder named videos/ in your project structure to store the video files you'll use for testing.

Note: Keep in mind that large binary files (like the shape predictor model) might not be suitable for Git repositories due to their size. You might consider using Git Large File Storage (Git LFS) for such files or hosting them separately.

Remember, the provided code is a basic example of driver drowsiness detection. Depending on your project's requirements, you might want to add more features, such as real-time alarms, data logging, and better user interfaces.
