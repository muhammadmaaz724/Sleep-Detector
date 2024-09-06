# Driver Drowsiness Detection with YOLOv8

## Overview
This project is a driver drowsiness detection system that identifies whether a driver's eyes are open or closed using real-time object detection. The application utilizes the YOLOv8s model to monitor the driver's eyes and sounds an alarm when closed eyes are detected for a specified duration. This solution aims to enhance road safety by preventing accidents caused by driver fatigue.

## Features
- **Real-time Eye Detection:** Detects open and closed eyes using the YOLOv8s model.
- **Driver Alert System:** Sounds a beep when closed eyes are detected, helping to prevent drowsy driving accidents.
- **Efficient Object Detection:** Utilizes YOLOv8s for fast and accurate eye state detection.
- **Customizable Alert Duration:** Configurable threshold for how long eyes must be closed before triggering the alarm.

## Model Details
- **YOLOv8s:** Lightweight version of the YOLO (You Only Look Once) object detection model, designed for real-time performance.
- **Training Data:** The model was trained using a combination of 2 datasets from roboflow.
- **Application:** Detects drowsy drivers to improve road safety, with potential use in vehicles for real-time driver monitoring.

## How It Works
1. **Capture Input:** The model continuously monitors the driver's eyes via a camera feed.
2. **Eye State Detection:** The YOLOv8s model detects whether the driver's eyes are open or closed.
3. **Trigger Alert:** If eyes are detected as closed for a specified period, an audible beep alert is triggered to wake the driver.

## Use Cases
- **Driver Safety Systems:** Can be integrated into vehicles to prevent accidents caused by driver fatigue.
- **Fleet Management:** Useful for monitoring driver attentiveness in commercial vehicles.
  
## Future Improvements
- **Face and Head Position Detection:** Expand the model to include head position for a more comprehensive drowsiness detection system.
- **Multi-Camera Integration:** Add support for multiple camera angles for enhanced monitoring in different lighting conditions.
