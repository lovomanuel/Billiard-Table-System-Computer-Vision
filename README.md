# BilliardFinalProject

## Project Description
This project focuses on various computer vision tasks related to billiards, including ball segmentation and classification, tracking, and metrics computation. The project is divided into several executable components, each handling specific aspects of the task.

## Requirements
- CMake (version 3.5 or higher)
- OpenCV (ensure it is installed and available in your system)

## Project Structure
Final_Project_CV_codes/
├── include/ # Header files
├── src/ # Source files
│ ├── Main_Field_Balls.cpp //Done by me
│ ├── Balls_segmentation.cpp //Done by me
│ ├── ball_classification.cpp
│ ├── Classes.cpp //Done by me
│ ├── Field_detection.cpp //Done by me
│ ├── Utilities.cpp //Done by me
│ ├── Metrics.cpp //Done by me
│ ├── main_tracking.cpp
│ ├── tracking.cpp
│ ├── table_orientation.cpp
│ ├── Main_metrics.cpp //Done by me
│ ├── main.cpp
├── CMakeLists.txt
└── README.md

## Building the Project
Clone the repository and enter inside the folder with cd command

mkdir build
cd build

cmake ..

make

# IMPORTANT DISCLAIMER

This project has been developed by three different people. Each member of the group had different tasks. However, for the correctness of the code, I have updated all the codes, including those that were not developed by me.

I have specifically developed the codes for detecting the field of the billiard table, detecting and segmenting all balls inside different videos, and computing the metrics.

The file main.cpp runs all tasks. If you prefer not to run the code, I have also uploaded a report detailing the ideas used and other relevant information and a folder containing output videos obtained by tracking system (not developed by me).

