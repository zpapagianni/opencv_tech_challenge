# CV Technical Challenge

## Introduction
This is a tech challenge to see if you can build a simple motion detection, which should be possible from searching the internet and reading documentation. We are not expecting a finished product, but rather what you can achieve from say a few hours to half a day of searching.


## Tools
You have to use the following to complete the challenge:

1. OpenCV
2. Python 3 
3. cv2 and numpy modules

For example:

```
import cv2
import numpy


capture = cv2.VideoCapture(filename)
return_val, image = capture.retrieve()
...

```

## Expectation
There are various ways to build a motion detection, including:
1. HAAR cascades
3. Using accumulateWeighted or similar to detect foreground vs background
4. Subtract / Dilate / Erode
5. Etc.

Choose withever method appeals to you, you are not limited by just what is in this list.


## Output
There are 2 videos provided, "Motion.mp4" and "NoMotion.mp4". In the cast of the former, the script should detect motion and output a jpeg image for every bit of detected motion similar to "Example Output.jpg". In the case of the latter, the script should not detect any motion.

Any questions, please let me know by email or WhatsApp (number is in my signature).