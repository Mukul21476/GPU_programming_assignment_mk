This repository contains Python scripts for processing images and signal data. It includes functionalities for image manipulation such as converting images to grayscale and for signal processing operations like applying filters. The scripts are designed to handle common tasks encountered in data preprocessing and analysis pipelines.

Features:
Image Processing: Convert images (JPEG, PNG) to grayscale using the Python Imaging Library (PIL).

Signal Processing: Apply a simple moving average filter to signal data (CSV files) using numpy and pandas libraries.

Modular Structure: Organized scripts allow for easy integration into existing projects or pipelines.

Key Components:
main.py: Entry point script that orchestrates the processing of images and signal data.

utils.py: Contains utility functions such as the apply_filter function for signal processing.

Usage:
Setup: Clone the repository and install dependencies listed in requirements.txt.

Configuration: Set the data_dir and output_dir variables in main.py to point to your input data and desired output directories.

Execution: Run main.py to start processing. Processed images and signal data will be saved in the specified output_dir.

Requirements:
Python 3.x
Libraries: PIL (Python Imaging Library), numpy, pandas
