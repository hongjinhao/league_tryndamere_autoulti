# Tryndamere Health Detection and Auto-Ultimate Script

This project contains a Jupyter Notebook containing a Python script for detecting the health of the League of Legends character Tryndamere and automatically activating his ultimate ability when his health drops below a certain threshold.
And several other useful python scripts to adapt the python script for your computer

## Overview

The script uses several Python libraries to perform screen capturing, image processing, and simulating keyboard input. The main components are:

- `mss`: Used to continuously capture screen regions.
- `opencv`: Processes the captured images to detect the health level.
- `pydirectinput`: Simulates keyboard input to activate Tryndamere's ultimate ability.

## Scripts

### 1. Health Detection and Auto-Ultimate Activation

This script captures a specific screen region, processes the image to detect the health level of Tryndamere, and presses 'R' if the health is below a certain percentage.

### 2. Screenshot Testing
This script is used to test if the specified region for capturing the screen is correct.


### 3. Color Detection at Mouse Location
Use this script to find the colors at a specific mouse location. It's useful for debugging and setting the upper and lower boundaries of the color detection.


## Setup

Install the required packages:

```bash
pip install opencv-python mss pydirectinput pynput
```

## Note
This script is intended for educational purposes and should not be used to gain an unfair advantage in games.
