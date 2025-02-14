# ships_detection_in_satellite_imagery
Ship Detection using YOLOv3
Dataset Overview
This project utilizes a dataset containing 26.9k images, specifically curated for ship detection. Each image is annotated using the YOLO format, ensuring accurate and efficient detection of ships. The dataset is limited to a single class ("ship"), allowing for streamlined training and evaluation.

Applications of Ship Detection
Ship detection has numerous practical applications, including:

Maritime Safety – Preventing collisions and ensuring navigational safety.
Fisheries Management – Monitoring fishing activities and preventing overfishing.
Marine Pollution Monitoring – Identifying ships involved in pollution incidents.
Defense & Maritime Security – Enhancing border security and monitoring unauthorized vessels.
Anti-Piracy & Illegal Immigration – Detecting and tracking unauthorized or suspicious activities.
Model & Implementation
YOLOv3 for Ship Detection
We trained the YOLOv3 (You Only Look Once) model to detect ships in images. YOLOv3 is a powerful object detection algorithm that balances accuracy and speed, making it well-suited for real-time applications.

Implementation Details
Framework: PyTorch & OpenCV
Training Environment: Google Colab
Pretrained Weights: YOLOv3 pretrained on COCO dataset
Input Image Size: 416x416
Loss Function: Binary Cross-Entropy & Mean Squared Error
Optimizer: Adam/SGD
Augmentations: Resizing, flipping, and color adjustments
Results
Achieved high accuracy in detecting ships across various images.
Improved real-time inference speed, making it suitable for maritime applications.
Successfully deployed on Google Colab, leveraging GPU acceleration for faster training.
Usage
Open in Jupyter Notebook or can use google colab
Future Improvements
Experimenting with YOLOv8 for improved accuracy and efficiency.
Deploying the model as a real-time API for maritime surveillance.
Fine-tuning on additional weather-variant datasets for robustness.
References
YOLOv3 Paper: https://arxiv.org/abs/1804.02767
Dataset: https://www.kaggle.com/datasets/siddharthkumarsah/ships-in-aerial-images
