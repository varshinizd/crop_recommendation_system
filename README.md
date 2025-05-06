This project is a machine learning-based web application designed to recommend the most suitable crop to cultivate based on various soil and environmental parameters. The application uses a Random Forest Classifier for prediction and is deployed using the Flask framework.

Features
Predicts optimal crops (e.g., Rice, Wheat, Chickpea) based on input features:

Nitrogen

Phosphorus

Potassium

Temperature

Humidity

pH

Rainfall

Simple web interface for input and result display

Trained model is saved and loaded using pickle

Web application built with Flask and served via a basic HTML/CSS frontend

Technologies and Libraries Used:

Python

Pandas

Scikit-learn

model_selection

ensemble (RandomForestClassifier)

metrics (for accuracy measurement)

Pickle (for model serialization)

Flask (for deploying the web application)

VS Code (development environment)

HTML, CSS (frontend technologies)

Directory Structure
Trained model is stored as a .pkl file in the same directory as the Jupyter Notebook used for training

app.py - Flask backend application

templates/ - Contains HTML and CSS files

Future Enhancements:

Integration of real-time sensors to gather live data from the field
Dynamic crop recommendation based on continuously updated environmental inputs

Run this in your terminal:
1. Clone the Repository:
   git clone https://github.com/varshinizd/crop-recommender-system.git
   cd crop-recommender-system
   
3. Install Dependencies
   pip install -r requirements.txt
   This installs all Python libraries listed in the requirements.txt file.

4. Run the Flask App:
   python app.py
   This launches your Flask app locally.

4. Access the Web App
   Open your browser and go to: http://127.0.0.1:5000/

