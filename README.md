# MOT-yolo11

A Multi-Object Tracking (MOT) project utilizing YOLO11 for object detection and algorithms like ByteTrack, BoT-SORT, and DeepSORT for tracking.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Introduction

The aim of this project is to create a robust and efficient pipeline to track small spider species, particularly social spiders, in realistic environments. This is a challenging task due to the spiders' tiny size, erratic movements, and the heterogeneous and cluttered backgrounds in which they are typically found.

To the best of our knowledge, no existing research or model has successfully achieved consistent multi-object tracking of such small arthropods in real-world settings. Most existing object tracking frameworks are tuned for larger and more distinguishable subjects under controlled environments.

This project fills that gap by integrating:
- YOLO11 for precise detection,
- BoT-SORT and ByteTrack for advanced tracking,

Ultimately, the goal is to provide a foundational pipeline for further research and applications in ethology, ecology, and automated behavioral analysis of social spiders.

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
