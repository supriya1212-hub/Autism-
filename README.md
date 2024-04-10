Therapist and Child Engagement Analysis

Eye Tracking ,Object Gaze Detection & emotion detection
This Python script performs eye tracking and object gaze detection using computer vision techniques. It captures video frames from a source (video file), detects eyes, tracks the gaze direction, and calculates the position of the gaze on a virtual screen. Additionally, it records the time spent looking at each object.

Requirements:

Python 3.x
OpenCV (opencv-python)
NumPy (numpy)
PyAutoGUI (autopy)
Pygame (pygame)
Matplotlib (matplotlib)
Tensor flow
pytorch

Usage:

Ensure you have the necessary Python libraries installed.
Place the video file you want to analyze in the same directory as the script.
Replace 'child gesture.mp4' with the name of your input video file in the script.
Run the script.
While the script is running, it will display the video feed with eye detection and gaze tracking overlaid.
Press the 'Esc' key to exit the program.

Output:

The script records the x and y positions of the gaze and plots them on a scatter plot.
The scatter plot will display the trajectory of the gaze over time.
The plot window will automatically close once the program finishes execution.
Functionality
The script detects eyes in the video feed using image processing techniques.
It tracks the movement of the gaze by analyzing the position of the detected eyes.
When an object gaze is detected, it records the time spent looking at that object.
The script displays the gaze position in a virtual screen created using Pygame.
It provides real-time visualization of the eye tracking process and object gaze detection.

Notes:

Adjust the video file name and file path according to your setup.
Fine-tune parameters such as image processing filters and eye detection thresholds for better accuracy.
Ensure the video frame resolution matches the resolution settings in the script.
Customize the script further as needed for your specific use case.
This README provides an overview of the eye tracking ,emotion detection object gaze detection script, its requirements, usage instructions, and functionality details. Feel free to add more details or sections as necessary based on your project's requirements and audience.
