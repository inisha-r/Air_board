# Air Board

**Air Board** is a Python-based virtual drawing application that allows users to draw in the air using hand gestures. It uses real-time webcam input, MediaPipe for hand landmark detection, and OpenCV for visualization and interaction.

## Features

* Real-time hand tracking using MediaPipe
* Virtual drawing on a blank canvas using finger movements
* Live webcam feed with overlaid drawings
* Press `'q'` to exit the application

## Demo

![Air Board Demo](demo.gif)
*(Replace with your demo GIF or video)*

## Requirements

* Python 3.7+
* OpenCV
* MediaPipe
* NumPy

## Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/air-board.git
cd air-board
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install opencv-python mediapipe numpy
```

## Usage

Run the notebook or the script:

```bash
python main.py
```

Or open `main.ipynb` in Jupyter Notebook and run the cells.

## Controls

* Use your index finger to draw in the air.
* Drawings are shown in real-time on the screen.
* Press `q` to quit the application.

## License

MIT License

---
