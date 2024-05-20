
# Motion Detection Alarm System
## Overview
This project is a simple motion detection alarm system using OpenCV and Python. The system captures video from a webcam, processes the frames to detect motion, and triggers an alarm when significant motion is detected.

## Code Explanation
### Motion Detection Logic
The script initializes the webcam and captures the initial frame to use as a reference. It then continuously captures frames and compares them to the reference frame to detect motion. If the difference exceeds a certain threshold, it triggers an alarm.

### Alarm Function
The beep_alarm() function is executed in a separate thread when significant motion is detected. It emits a beep sound using the winsound module.


## Main Loop
The main loop captures video frames, processes them for motion detection, and displays the result. It checks for user input to toggle the alarm mode or quit the application.

## Key Controls:

#### t: Toggle alarm mode on/off.
#### q: Quit the application.
