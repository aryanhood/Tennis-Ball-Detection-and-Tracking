
# Tennis Ball In/Out Detection Algorithm

This project provides an algorithm to detect whether a tennis ball lands "In" or "Out" based on high-speed video feeds. The system processes each shot and updates the score in real-time.

## Problem Scope

- **Input**: High-speed video feed (e.g., 60 FPS or higher) from cameras.
- **Output**: Decision for each shot ("In" or "Out") and score updates.

## Features

- Detects tennis ball trajectory in video frames.
- Classifies each shot as "In" or "Out".
- Updates match score automatically based on shot decisions.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- (Optional) TensorFlow/PyTorch (if using machine learning models)

Install dependencies using:

```
pip install -r requirements.txt
```

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/your-username/tennis-ball-detection.git
   ```

2. Navigate to the project folder:

   ```
   cd tennis-ball-detection
   ```

3. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

## Usage

1. Place your video file in the `input_videos/` folder.

2. Run the detection script:

   ```
   python detect_ball_in_out.py --video_path input_videos/your_video.mp4
   ```

   The algorithm will analyze the video and output whether each shot is "In" or "Out", while updating the score.

## Directory Structure

```
tennis-ball-detection/
│
├── input_videos/          # Input video files
├── output/                # Results and logs
├── detect_ball_in_out.py  # Main detection script
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

## Contributing

Feel free to fork the repository, create a branch, and submit pull requests. Improvements and bug fixes are welcome.

---
