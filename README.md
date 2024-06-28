# Vehicle Speed Detection from Video

This project involves detecting vehicles in a video stream, calculating their speed based on line crossing detection, and logging relevant information.

## Features

- **Vehicle Detection**: Detect vehicles in video frames.
- **Speed Calculation**: Calculate the speed of vehicles based on the time taken to cross predefined lines.
- **Line Crossing Detection**: Detect when a vehicle crosses a predefined line in the video.
- **Tracking**: Track multiple vehicles using unique IDs.
- **Logging**: Log the speed and other details of the vehicles.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Additional dependencies can be installed via `requirements.txt`.

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/Fukuiz/Speed-calculation.git
    cd Speed-calculation
    ```

2. **Install the required libraries:**

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Prepare your video file**: Ensure you have a video file for processing. Place it in the appropriate directory or update the script with the correct path.

2. **Run the Jupyter Notebook**: Open `execute.ipynb` in Jupyter Notebook or Jupyter Lab and run the cells sequentially.

## File Descriptions

- **execute.ipynb**: Jupyter Notebook containing the main code for vehicle detection, speed calculation, and line crossing detection.
- **tracker.py**: Python file containing the `Tracker` class used for tracking multiple vehicles.

## Tracker Class

The `Tracker` class is responsible for tracking objects in video frames by maintaining their center points and assigning unique IDs to them.

### Key Functions

- **Object Detection**: Uses a pre-trained model to detect vehicles in video frames.
- **Line Crossing Detection**: Detects when vehicles cross predefined lines in the video.
- **Speed Calculation**: Calculates the speed of vehicles based on the time taken to cross the lines.
- **Tracking**: Tracks multiple vehicles using unique IDs, ensuring that the same object is consistently identified across frames.

## Example

1. **Load the video**: Load your video file into the notebook.
2. **Define the lines**: Set the coordinates for the lines used for speed calculation.
3. **Run the detection**: Execute the cells to run the vehicle detection and speed calculation.

## Disclaimer

This software is intended for educational purposes only. Use it responsibly and ensure you have permission to process the video files.



for the coodinate of the line you can go to https://roboflow.github.io/polygonzone/ 
![Capture](https://github.com/Fukuiz/Speed-calculation/assets/162476251/79c432bc-b7c7-4846-b533-f2fb555bc4e5)
