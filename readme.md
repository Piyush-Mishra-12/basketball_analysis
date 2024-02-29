
# Basketball Dribbling Analysis

## Overview

This repository focuses on applying computer vision techniques to analyze a basketball dribbling sequence captured in a video. The primary objectives include determining the total count of dribbles, quantifying dribbles performed by each hand individually, and keeping a record of ball transitions between the player's hands during the dribbling sequence and lastly determine weather the person is right handed or left handed.

## Dataset Preparation

The dataset, obtained through the [Roboflow](https://roboflow.com/) platform, consists of 156 images. Annotations for the "Ball," "Floor," "Left Hand," and "Right Hand" were provided in YOLOv8 Oriented Object Detection format. Pre-processing involved auto-orientation, resizing, and augmentation to enhance the dataset's variability.

## Model Training

The YOLOv8 model was trained on the annotated dataset using the [Ultralytics](https://github.com/ultralytics/yolov5) library. Training metrics, including Mean Average Precision (MAP), demonstrated the model's proficiency in object detection tasks.

## Model Inference

The trained model was applied to a video capturing basketball dribbling. The resulting predictions were visualized and analyzed to understand the player's interactions with the ball.

## Results and Analysis

The analysis involved calculating distances between key points such as the ball center, hand bottom center, and floor center. Events, including bounces and hand dribbles, were identified based on these distances. Transitions between hands were also counted, providing insights into the player's dribbling patterns.

## Conclusion

This repository serves as a comprehensive guide to analyzing basketball dribbling through computer vision techniques. The provided code and analysis can be adapted for similar projects or serve as a starting point for further exploration in sports analytics. Feel free to explore the code, experiment, and contribute to enhance the capabilities of this analysis. If you have any questions or feedback, please don't hesitate to reach out.

>>>>>>> f916bc21c32bcac1cf39dd2a8530b37965886b22
Happy coding! 🏀✨
