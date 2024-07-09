# Ball Tracking and Event Recording using Computer Vision

This project uses OpenCV and Python to track the movement of colored balls in a video and records the events when a ball enters or exits a specific quadrant. The processed video, along with a CSV and a text file containing the recorded events, is saved for further analysis.

## Project Structure

- `ball_tracking.py`: Main script that processes the video, tracks balls, and records events.
- `requirements.txt`: List of Python packages required to run the project.
- `README.md`: Documentation for the project.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Pandas
- Google Colab (for running the script in a Jupyter notebook environment)

## Setup

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/ball-tracking-event-recording.git
    cd ball-tracking-event-recording
    ```

2. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Run the script in Google Colab**:
    Open the script in a Colab notebook, copy the code, and execute it. You will be prompted to upload a video file for processing.

## Usage

1. **Upload a video file**:
    When prompted in Google Colab, upload the video file you want to process.

2. **Processing the video**:
    The script will process the video to track the colored balls and record events when a ball enters or exits a quadrant. The processed video and event data files will be saved.

3. **Download the results**:
    The processed video, CSV file, and text file containing the events can be downloaded using the links provided after the processing is complete.

## Output

The script generates the following outputs:

- **Processed Video**: The video with ball tracking and overlay text for entry/exit events.
- **CSV File**: A CSV file containing the event data in the format:
    ```
    Time, Quadrant Number, Ball Colour, Type
    ```
- **Text File**: A text file containing the event data in the format:
    ```
    Time, Quadrant Number, Ball Colour, Event Type (Entry or Exit)
    ```


