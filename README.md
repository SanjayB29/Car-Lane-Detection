# Car Lane Detection

## Overview
This project focuses on detecting lanes on roads to enhance driver assistance systems. By utilizing a combination of NumPy and OpenCV in Python, this project aims to improve vehicle navigation through accurate lane detection. The algorithm processes images from the Carla Driving Simulator dataset, identifies lane markings, and highlights the lanes the vehicle should follow.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Setup](#setup)
- [Contributing](#contributing)

## Features
- Lane detection using NumPy and OpenCV.
- Data augmentation and preprocessing for robust model training.
- Utilization of Segmentation Models PyTorch for semantic segmentation.
- Evaluation of model performance on a validation set.

## Requirements
The project requires the following dependencies:
- Python 3.x
- Kaggle
- NumPy
- Pandas
- OpenCV
- PyTorch
- Albumentations
- Segmentation Models PyTorch

For a complete list of requirements, please refer to the `requirements.txt` file in the repository.

## Setup
To set up the project environment, follow these steps:

1. Clone the repository:
git clone https://github.com/SanjayB29/Car-Lane-Detection.git

markdown
Copy code
2. Install the required dependencies:
pip install -r requirements.txt

vbnet
Copy code
3. Follow the instructions in the Jupyter Notebook (`CarLaneDetection.ipynb`) to download the dataset and run the detection model.

## Contributing
Contributions to the Car Lane Detection project are welcome! Here's how you can contribute:
- Fork the repository.
- Create a new branch for your feature (`git checkout -b feature/AmazingFeature`).
- Commit your changes (`git commit -m 'Add some AmazingFeature'`).
- Push to the branch (`git push origin feature/AmazingFeature`).
- Open a pull request.
