Facial Recognition and Data Logging System
Welcome to the Facial Recognition and Data Logging System! This advanced solution is designed to detect faces in video feeds, verify them against a predefined dataset, and update a CSV file with the relevant information. Follow these easy steps to use the system:

Prerequisites
First, install the required libraries by running:

pip install -r requirements.txt
Image Naming Convention
Make sure your image files follow this naming format: "Name Number.jpg" (e.g., "Shukur 1.jpg").

Training the Face Detection Model
Train the face detection model by executing:


python train_model.py
Then, run main_work.py to identify faces, compare them with the dataset, and add the data to the CSV file:


python main_work.py
The system will automatically update the CSV file with relevant information whenever it detects a match. Enjoy the benefits of effective facial recognition and efficient data management!




