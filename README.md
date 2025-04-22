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
![Dataset Video 1](media/data/data1.gif)
![Dataset Video 2](media/data/data2.gif)
   
### Final output demo:
![ByteTrack Output 1](media/results/byte1.gif)
![Bot-SORT Output 2](media/results/bot2.gif)
