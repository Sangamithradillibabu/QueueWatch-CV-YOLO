Project OverView:
This project focuses only on queue detection and monitoring, specifically designed for election polling booths. It uses a custom-trained YOLOv8 people detection model to count voters in a queue and classify the situation into risk levels for better crowd and resource management.

Project Objective

To automatically:
1.Detect people standing in a queue
2.Estimate actual voter count
3.Classify queue status (LOW / MEDIUM / HIGH)
4.Suggest actions for election authorities

Use Case
 Election Queue Monitoring:
 
1.Avoid long waiting times
2.Prevent overcrowding
3.Decide when to deploy extra staff or voting machines

Tech Stack:

Python
YOLOv8 (Ultralytics)
Roboflow (Custom dataset)
OpenCV
Google Colab

Model Weights:

Trained model file: best.pt
Generated after training in Google Colab
