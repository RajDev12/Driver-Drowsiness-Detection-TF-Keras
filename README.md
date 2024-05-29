# Drowsiness Detection System

## Overview
This repository contains a comprehensive Drowsiness Detection System designed to improve road safety by monitoring drivers for signs of fatigue. Leveraging advanced computer vision and machine learning techniques, this system can accurately detect and alert drivers when they show signs of drowsiness.

## Features
- **Real-time Detection:** Utilizes a webcam to continuously monitor the driver's facial features.
- **Eye State Analysis:** Analyzes the driver's eye state (open or closed) to determine drowsiness levels.
- **Yawning Detection:** Identifies yawning patterns as an indicator of fatigue.
- **Alert System:** Provides audio and visual alerts to warn drivers when drowsiness is detected.
- **Customizable Sensitivity:** Allows customization of detection sensitivity to reduce false positives.
- **Cross-Platform Compatibility:** Designed to run on multiple operating systems, including Windows, macOS, and Linux.

## Technologies Used
- **OpenCV:** For image and video processing.
- **Dlib:** For facial landmark detection.
- **TensorFlow/Keras:** For implementing machine learning models.
- **Python:** The core programming language for the system.

## Installation
### Getting Started
1. Clone the repository:
    ```
    git clone https://github.com/dsshivamsingh/drowsiness-detection.git
    cd drowsiness-detection
    ```
2. Install the necessary dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Create required folders:
    ```
    mkdir models data
    ```
4. Download and organize the dataset:
    - Download the dataset from [Kaggle](https://www.kaggle.com/).
    - Extract the contents and place the `train` and `test` folders into the `data` directory.
    - Rename the `test` folder to `valid`:
        ```
        mv data/test data/valid
        ```
5. Train your model: Run the following script to train your model:
    ```
    python models.py
    ```
6. Run the main script to start the drowsiness detection system:
    ```
    python main.py
    ```
   Ensure your webcam is connected and properly configured. The system will begin monitoring and provide alerts as needed.

## Usage
Once the installation and setup are complete, you can use the system to detect drowsiness in real-time.

## Contributing
We welcome contributions from the community! If you have ideas for improvements or new features, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss your proposed modifications.

## Acknowledgments
We would like to thank the developers of OpenCV, Dlib, and TensorFlow for their powerful libraries, as well as the open-source community for their invaluable contributions.
