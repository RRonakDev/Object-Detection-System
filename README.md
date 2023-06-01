# Object Detection and Tracking

This code snippet demonstrates object detection and tracking using YOLO (You Only Look Once) and a tracking algorithm.

## Description

The code uses the YOLO model for object detection and a custom tracking algorithm to track objects in a video. It reads frames from an input video, performs object detection using YOLO, and then updates the tracker with the detected objects. The tracked objects are visualized by drawing bounding boxes around them in each frame. Finally, it saves the processed frames as an output video.

## Prerequisites

- Python 3.6+
- OpenCV
- TenserFlow

Install the required packages using the following command:

```bash
pip install -r requirements.txt
```

## Usage

- Place the input video file in the "assets" directory.
- Update the video_path variable in the code with the correct path to the input video file.
- Run the script.

```bash
python main.py
```

- The processed video will be saved as "out.mp4" in the current directory.

## Demo 

- Normal video







https://github.com/RRonakDev/Object-Detection-System/assets/102300772/2b3275c2-9fdc-4ecb-8b2d-8f4d53b934fc



- Output video







