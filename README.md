Ishaan-Poojari-CV Practical

Name: Ishaan Poojari


Problem 1:

The ColorIdenitfier class determines whether a bounding box contians a red or blue plate. The input color frame becomes an HSV, and the red and blue masks isolate the red and blue colors in the frame. The findContours function calculates the total area of each color for each masked frame and the color with the greater area is determined to be the color of that armor plate. 

The Capture class takes the video as input and analyzes each frame. The object detection pipeline is run for each frame using the process_frame() method, and the bounding box confidence is compared to the confidence threshold of 0.25. Bounding boxes above the threshold are shown with a respective confidence score.

Using the red and blue masks is advantageous as it reduced data overhead and elminates addiitonal attributes that are unnecessary for the armor plate detection. Calculating the contours from the masked frames makes the algorithm much faster.

Problem 2:

The DepthCamera class takes frames as input and produces the coordinates of the bounding boxes and the angle offsets for the shooter. The get_coordinates() function takes in a frame and outputs the coordinates of the bounding box as a tuple. The det_move() function takes in the coordinates of an objects and caluculates the angle offsets for the robot. 


Problem 3:

I based my systemD file after the systemD file in the tutorial. The systemD file runs the CV pipeline after every time the machine restarts. The file is copied to /etc/systemd/system/ and run from there.


