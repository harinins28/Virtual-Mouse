# Virtual-Mouse
# Virtual Mouse Using OpenCV

## Description
This Python code uses the Mediapipe library to detect hand landmarks in a video stream from a webcam. It then maps the position of the index finger and thumb to the screen coordinates and uses the PyAutoGUI library to control the mouse cursor.

## Dependencies
- OpenCV
- Mediapipe
- PyAutoGUI

## Usage
1. Connect a webcam to your computer.
2. Install the dependencies using pip or any other package manager:
    ```bash
    pip install opencv-python mediapipe pyautogui
    ```
3. Run the Python script:
    ```bash
    python virtual_mouse.py
    ```
4. Hold your hand up in front of the webcam.
5. Move your index finger to move the mouse cursor.
6. Bring your thumb close to your index finger to click the mouse.
## Output
![WhatsApp Image 2023-10-16 at 21 00 20_603b5f43](https://github.com/user-attachments/assets/b91c38fb-b65f-4099-a77e-4cc4aff34d5c)

## Note
This code is just a basic implementation and may not work accurately for everyone. You can tweak the code to adjust the sensitivity and threshold values for better accuracy.
