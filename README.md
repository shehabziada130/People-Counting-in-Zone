# People Counting in Zone

This project aims to count the number of people entering a specific area in a video stream. It utilizes YOLO (You Only Look Once) object detection to detect people in the video frames and tracks their movement using centroid tracking. The count is incremented each time a person crosses a defined line in the video.

## Features
- Detection and tracking of people in a specified area of the video.
- Counting the number of people entering the designated area.
- Drawing a line on the video to define the counting area.
- Displaying real-time counts on the video.

## Requirements
- Python 3
- OpenCV
- NumPy
- Pandas
- CVZone
- Ultralytics YOLO (yolov8s.pt)
- Tracker module (provided separately)
- Hikvision camera (for the camera stream analysis)

## Installation
1. Clone the repository:

git clone  https://github.com/s/repo](https://github.com/shehabziada130/People-Counting-in-Zone.git


2. Install the required dependencies:

pip install numpy pandas opencv-python
pip install cvzone
pip install yolov5 # Ultralytics YOLO



## Usage
### Running the Video Analysis Script
1. Place the video file named "input_vidoe.mp4" in the project directory.
2. Run the script `video_analysis.py`:
3. The script will process the video, detect people, track their movement, and count the number of people entering the defined area.

### Analyzing a Stream from Hikvision Camera
To analyze a video stream from a Hikvision camera, follow these steps:

1. Ensure the camera stream is accessible on the network.
2. Modify the script `video_analysis.py` to include the appropriate IP address and credentials for accessing the camera stream.
3. Run the script
4. The script will analyze the video stream from the Hikvision camera, detecting and counting people entering the designated area.

## Output
- The output of the video analysis script will be a video file named "output_video.mp4" containing the processed video with the counting area drawn and real-time count displayed
  You can Access it here "https://drive.google.com/file/d/1sq4ZSZHvJTsVZp_PzVuSeAOvR-k9aIdV/view?usp=sharing".
- For the Hikvision camera stream analysis, the output will be the real-time count of people entering the designated area displayed on the console.

