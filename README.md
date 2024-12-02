

##Tomato Leaf Disease Prediction Using Deep Learning

#Overview

Tomatoes are one of the most important and widely cultivated crops globally, and their production is significantly affected by leaf diseases. These diseases reduce the quality and quantity of the yield, directly impacting agricultural productivity. Early identification and classification of tomato leaf diseases are essential for mitigating their effects and ensuring healthy crop growth.

This project leverages Deep Learning techniques, specifically Convolutional Neural Networks (CNNs), to accurately identify and classify various tomato leaf diseases. By providing an efficient method for early detection, this model aims to assist farmers in diagnosing diseases at an early stage, thereby improving crop productivity and reducing economic losses.

#Features

	•	Disease Detection and Classification:
	•	Identifies various tomato leaf diseases based on input images.
	•	Employs CNNs for robust and accurate classification.
	•	User-Friendly Interface:
	•	A web-based interface for users to upload images and get predictions.
	•	Facilitates an easy-to-use experience for farmers and agriculturalists.
	•	Automated Workflow:
	•	Automatically processes uploaded images to provide results.
	•	Supports batch processing for multiple images.

#Dataset

	•	Source: Kaggle or custom-curated tomato leaf datasets.
	•	Structure:
	•	Contains labeled images of healthy and diseased tomato leaves.
	•	Categories include diseases such as Tomato Mosaic Virus, Early Blight, Late Blight, etc.

#Technology Stack

	•	Deep Learning Framework: TensorFlow/Keras
	•	Model Architecture: Convolutional Neural Networks (InceptionV3)
	•	Backend: Flask for serving predictions.
	•	Frontend: HTML/CSS templates for user interaction.
	•	Deployment: Local or cloud-based deployment for scalability.

#Project Structure

Tomato Leaf Disease Prediction/
│
├── static/                # Static files (CSS, JS, Images)
├── templates/             # HTML templates for web interface
├── uploads/               # Directory for uploaded images
├── app.py                 # Flask application for the project
├── Tomato_inceptionv3.ipynb  # Jupyter Notebook for model training
├── README.md              # Project description

#Installation and Setup

Prerequisites

	•	Python 3.x
	•	Required libraries: TensorFlow, Keras, Flask, NumPy, OpenCV, etc.

Steps

	1.	Clone the repository:

git clone https://github.com/Nikitha130731/Tomato-leaf-detection-using-CNN.git
cd tomato-leaf-disease-prediction


	2.	Install dependencies:

pip install -r requirements.txt


	3.	Train the model (optional if weights are already included):
	•	Open Tomato_inceptionv3.ipynb and run all cells to train the model.
	4.	Run the application:

python app.py


	5.	Access the web interface at http://localhost:5000.

Results

The model achieved the following performance metrics:
	•	Accuracy: 90%+
	•	Loss: Minimal loss across training and validation datasets.

Usage

	1.	Launch the application and upload an image of a tomato leaf.
	2.	The application will process the image and provide:
	•	The identified disease (if any).
	•	Recommendations for managing the disease.

Future Enhancements

	•	Expand the dataset to include more diseases.
	•	Enhance the model to improve accuracy further.
	•	Deploy the application on cloud platforms for broader access.
	•	Add multi-language support for user accessibility.

#Contributing

Contributions are welcome! Please create a pull request for suggestions or improvements.

License

This project is licensed under the MIT License. See LICENSE for more details.

Replace "https://github.com/Nikitha130731/Tomato-leaf-detection-using-CNN.git" with your actual GitHub repository URL. Let me know if you need help adding more details!
