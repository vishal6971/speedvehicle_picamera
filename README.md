# speedvehicle_picamera
 My program is based on the motion detection program found on the pyimagesearch.com site with modifications for speed detection. Not only does the program need to detect motion, it needs to time the moving car as it passes across the camera’s field of view, and it needs to know how far the car traveled.
 
This is what we will ask the motion detection part of the program to do:

-detect motion using the logic presented at the pyimagesearch site
-begin a timer
-track the moving object until it reaches the opposite side of the frame.
-calculate the speed
-save a picture of the image labeled with the speed calculated
