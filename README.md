## Facial Recognition and Data Logging System
Welcome to the Face Detection and Data Addition System! This robust solution is designed for detecting faces in video, verifying them against a predefined dataset, and updating a CSV file with relevant data. To seamlessly use this system, follow these straightforward steps:

## Prerequisites
Install the necessary libraries by executing:

pip install -r requirements.txt

Image Naming Convention
Ensure your image files adhere to this naming convention: "Name Number.jpg" (e.g., "Shukur 1.jpg").

## Train the face detection model by running:
python train_model.py
Execute main_work.py to identify faces, cross-reference the dataset, and append data to the CSV file:
python main_work.py
The system automatically updates the CSV file with relevant data upon finding a match. Experience the power of facial recognition and streamlined data management in action!