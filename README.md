## Overview

The project will propose a derivative application of fa- cial landmark detection - a driver drowsiness detection model. This model will incorporate real-time eye open- ness tracking with fail-safe mechanism. To track on the head pose along with eye blink detection, and this model would have more versatile in the situations where the camera is unable to capture the eye area and can also help detect the drivers’ distraction while driving. The 68 facial landmark detector, from ibug research group, can help locate the driver’s face. During the experimental test on driving tapes, the algorithm will use theses land- marks for further process. The supportive head pose estimation approach is triggered when EAR is under the default threshold and implies the irregular eye contour turbulence. The final evaluation from above approaches will be made to fill the gap on dependency of single method.

#### Get Pose From Image

```
python head_pose_from_image.py -h
```

#### Get Pose From Webcame

```
python head_pose_from_webcam.py -h

```
