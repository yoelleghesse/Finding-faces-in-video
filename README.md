This script takes a video file (video.mp4) as input and detects faces using a pre-trained Haar cascade classifier. It draws bounding boxes around the detected faces and saves the modified video with bounding boxes as output (output.avi).

Install OpenCV:

``pip install opencv-python``

Place the video file (video.mp4) you want to analyze and a Haar cascade classifier file (faces.xml) in the project folder.

Run the script:

``python video_face_detection.py``

The modified video with bounding boxes around detected faces will be saved as output.avi in the project folder.
