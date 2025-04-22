# MOT-yolo11

A Multi-Object Tracking (MOT) project utilizing YOLO11 for object detection and algorithms like ByteTrack, BoT-SORT, and DeepSORT for tracking.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

This project focuses on detecting and tracking 'social spiders dataset' using advanced object detection and tracking algorithms.

## Methodology

- **Detection**: Implemented using YOLO11.
- **Tracking**: Utilized built-in ByteTrack and BoT-SORT algorithms.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mohit3agarwal/MOT-yolo11.git

2. Navigate to project directory:
   ```bash
   cd MOT-yolo11

3. Install dependencies:
   ```bash
   pip install -r requirements.txt

## Usage

1. For Detection:
   Adjust the parameters and run the detections file
   ```bash
   python detections.ipynb

2. For Tracking:
   Adjust the parameters and run the tracking file
   ```bash
   python tracking.ipynb

## Results
Some of the results of the 'social spiders' dataset are as follows:

### Dataset example:
![Dataset Video 1](media/data/test1.mp4)
![Dataset Video 1](media/data/test2.mp4)
   
### Final output demo:

<video src="media/results/botsort/test2.mp4" controls width="600"></video>

<video src="media/results/bytetrack/test1.mp4" controls width="600"></video>
