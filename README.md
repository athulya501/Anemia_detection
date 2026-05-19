HemoScan – Non-Invasive Anemia Detection System

Overview
HemoScan is a machine learning-based web application designed to detect anemia non-invasively using fingertip images.
The system analyzes uploaded fingertip images through image processing and AI/ML techniques to predict the possibility of anemia without requiring traditional blood tests.
This project aims to provide a simple, fast, and accessible preliminary screening method for anemia detection.

Features
Upload fingertip images for analysis
Image preprocessing and feature extraction
Machine Learning-based anemia prediction
User-friendly web interface
Fast and non-invasive screening process

Technologies Used
Frontend
HTML
CSS
JavaScript

Backend
Python
Flask

Machine Learning & Image Processing
OpenCV
NumPy
Pandas
Scikit-learn

Working Principle
User uploads a fingertip image.
The system preprocesses the image using image processing techniques.
Important image features are extracted.
The trained machine learning model analyzes the features.
The system predicts whether the user may have anemia.

Project Structure
HemoScan/
│
├── static/
│   ├── css/
│   ├── js/
│   └── uploads/
│
├── templates/
│   └── index.html
│
├── model/
│   └── anemia_model.pkl
│
├── app.py
├── requirements.txt
└── README.md

Installation
Clone the Repository
git clone https://github.com/your-username/HemoScan.git
Navigate to the Project Folder
cd HemoScan
Install Dependencies
pip install -r requirements.txt
Run the Application
python app.py

Future Enhancements
Improve prediction accuracy using larger datasets
Add deep learning models
Mobile application integration
Real-time image capture support
Cloud deployment

Applications
Preliminary anemia screening
Rural healthcare assistance
Remote health monitoring
Low-cost health diagnosis support

Conclusion
HemoScan demonstrates how AI and image processing can be used in healthcare to create affordable and accessible diagnostic solutions. The project highlights the potential of non-invasive medical screening systems using machine learning.

License
This project is developed for educational and academic purposes.
