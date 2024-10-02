# Crowd_Detection using Computer-Vision

## INTRODUCTION

In densely populated areas such as urban environments, public events, and transportation hubs, monitoring crowd behavior is paramount for ensuring public safety and security. Traditional methods of surveillance and crowd management often rely on manual monitoring, which can be labor-intensive, time-consuming, and susceptible to human error. Moreover, as the complexity and scale of modern urban environments increase, the need for more sophisticated and efficient crowd monitoring solutions becomes increasingly pressing.

## PROBLEM STATEMENT

The project aims to address the challenge of effectively monitoring crowded environments by developing a computer vision system capable of autonomously detecting anomalies in crowd behavior. This involves creating robust algorithms to analyze live or recorded video feeds, distinguishing normal crowd patterns from abnormal events such as fights, accidents, or suspicious behavior, and facilitating timely interventions to ensure public safety and security.

## ABOUT THE DATASET

The mall dataset was collected from a publicly accessible webcam for crowd counting and profiling research.
Video length: 2000 frames
Frame size: 640x480
Frame rate: < 2 Hz The dataset is composed by RGB images of frames in a video (as inputs) and the object counting on every frame, this is the number of pedestrians (object) in the image. The images are 480x640 pixels at 3 channels of the same spot recorded by a webcam in a mall but it has different number of person on every frame, is a problem of crowd counting.

## OUR VISION

Our vision is to create a robust computer vision system capable of autonomously monitoring crowded environments, identifying anomalies in real-time.

## OUR GOAL

Our goal is to develop state-of-the-art deep learning models and deploy scalable surveillance solutions that enable early detection of crowd anomalies, thereby minimizing potential risks.

## METHODOLOGY

- **Data Preparation:** Collect and preprocess video data, including resizing and normalizing images.
- **Object Detection and Tracking:** Use pre-trained TensorHub models for object detection and implement tracking algorithms for continuity across frames.
- **Crowd Density Estimation:** Utilize Inception-ResNet model to estimate crowd density in different regions.
- **Behavior Analysis:** Analyze crowd behavior using features extracted from Inception-ResNet model.
- **Anomaly Detection:** Train anomaly detection models using features from both models to identify abnormal behavior.
- **Integration and Visualization:** Integrate components into a unified framework and develop a user-friendly interface for monitoring and alerts.
- **Evaluation and Optimization:** Evaluate system performance, fine-tune parameters, and optimize for real-world deployment

## RESULTS
