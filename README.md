# 470-FingerGunGame

## Requirements
* OpenCV
* Numpy
* Plain background

## Instructions
1. Run [skin-color-thresholds.ipynb](skin-color-thresholds.ipynb) to find thresholds that work in your environment. This changes depending on lighting and background colour. Aim to have the bottom screen show a whole outline of the hand.
2. Copy the thresholds that worked best from step 1 into [hand_gesture_recognition.ipynb](hand_gesture_recognition.ipynb), replacing y_min, y_max, cr_min, cr_max, cb_min, cb_max.
3. Run [hand_gesture_recognition.ipynb](hand_gesture_recognition.ipynb) to start the program
   - Note this works best with a 1920x1080 camera
4. Open your hand with fingers spread apart to start
5. Make finger-gun shape with hand, lower thumb on top of pointer finger to shoot
