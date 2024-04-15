## Real Time Video Glasses

### Description:
This Python script demonstrates real-time facial landmark detection and overlaying sunglasses on detected faces using OpenCV, dlib, and Haar Cascade classifiers.

### Requirements:
- Python 3.x
- OpenCV (cv2)
- dlib
- Requests
- NumPy

### Installation:

1. Clone the repository or download the Python script.

2. Install the required packages using pip:

```bash
pip install opencv-python dlib requests numpy
```

### Usage:

1. Run the Python script `overlay_sunglasses.py`.

```bash
python overlay_sunglasses.py
```

2. The webcam will open, and you'll see the video feed.

3. The script will detect faces in the video feed and overlay sunglasses on them in real-time.

4. Press 'q' to quit the application.

### Files:

- `overlay_sunglasses.py`: Python script for real-time facial landmark detection and sunglasses overlay.
- `sunglass.png`: Image file of sunglasses with an alpha channel for transparency.

### Additional Notes:
- Ensure your webcam is connected and working properly.
- The facial landmark detection model (`shape_predictor_68_face_landmarks.dat`) will be automatically downloaded if not found in the working directory. This may take some time on the first run.
- You may need to adjust the scaling factor and other parameters for better overlay results based on your environment and camera setup.
- The script utilizes Haar Cascade classifiers for face detection and dlib for facial landmark detection. Ensure these models are correctly configured and accessible.
- The sunglasses image (`sunglass.png`) can be replaced with any other transparent PNG image for different overlay effects.

### Acknowledgments:
- This script is based on the work of various contributors to the OpenCV, dlib, and NumPy libraries.
- The facial landmark detection model used in this script is provided by the dlib library.
- The sunglasses image used for overlaying is for demonstration purposes and can be replaced with any other image as desired.
