#   FastLane Detector

FastLane Detector is a Python-based application that utilizes OpenCV for detecting and estimating the speed of vehicles in video footage. By analyzing video frames, the application identifies moving vehicles and calculates their speeds, making it a valuable tool for traffic monitoring and analysis.

## Features

- **Vehicle Detection**: Identifies vehicles in video streams using pre-trained classifiers.
- **Speed Estimation**: Calculates the speed of detected vehicles based on frame analysis.
- **Video Processing**: Processes video files to analyze traffic flow and vehicle speeds.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/dyn-dal-037/FastLane-Detector.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd FastLane-Detector
   ```
3. **Install Dependencies**:
   Ensure you have Python installed. Install the required packages using pip:
   ```bash
   pip install -r requirements.txt
   ```
   *Note: If `requirements.txt` is not provided, the primary dependency is OpenCV. Install it using:*
   ```bash
   pip install opencv-python
   ```

## Usage

1. **Prepare the Video File**:
   Place the video file you want to analyze (e.g., `carsVideo.mp4`) in the project directory.

2. **Run the Speed Detector Script**:
   Execute the `speed_detector.py` script with the video file as an argument:
   ```bash
   python speed_detector.py --video carsVideo.mp4
   ```
   *Note: If the script does not support command-line arguments, you may need to modify the script to specify the video file path directly.*

3. **View the Results**:
   The script will process the video, detect vehicles, and display their estimated speeds in real-time.

## Dependencies

- Python 3.x
- OpenCV
- NumPy

*Ensure all dependencies are installed for the application to function correctly.*

