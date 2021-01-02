# InvisibleCloak
Make you become invisible with Python and OpenCV

# Describle
Uncompleted project. I hope can make this project become better in the future
# Technique
Very simple, remove the foreground frame:
1. Capture and store the background (save this in the temp.txt file and then just open and load it) 
2. Detect the defined color (in this code default used red color, you can change it on the Trackbar)
3. Segment out the defined color part by generating a mask
4. Replace the part in step 3 by the background saved in step 1
# How to use
Downloaded ```InvisibilityCloak.py``` and run by the command ``` python InvisibilityCloak.py ```
