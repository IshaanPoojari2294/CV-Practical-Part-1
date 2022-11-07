Ishaan-Poojari-CV Practical

Name: Ishaan Poojari


Problem 1:

Design Decisions:

The ColorIdenitfier class determines whether a bounding box contians a red or blue plate. The input color frame becomes an HSV, and the red and blue masks isolate the red and blue colors in the frame. The findContours function calculates the total area of each color for each masked frame and the color with the greater area is determined to be the color of that armor plate. 

The Capture class takes the video as input and analyzes each frame. The object detection pipeline is run for each frame using the process_frame() method, and the bounding box confidence is compared to the confidence threshold of 0.25. Bounding boxes above the threshold are shown with a respective confidence score.



Problem 2:




Problem 3:

I based my systemD file after the systemD file in the tutorial.  


