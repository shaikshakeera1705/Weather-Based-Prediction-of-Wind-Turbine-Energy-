🌬️ Weather-Based Prediction of Wind Turbine Energy Output
A Next-Generation Approach to Renewable Energy Management
📌 Project Description

This project predicts Wind Turbine Power Output using Machine Learning based on weather conditions such as wind speed, wind direction, temperature, humidity, and other environmental parameters.

The trained ML model is saved as a .sav file and integrated with a Flask web application. Users can enter weather values in the web interface, and the system predicts the expected wind turbine energy output instantly.

This system is useful for:
Renewable energy forecasting
Smart grid management
Power planning and scheduling
Reducing energy wastage

🎯 Project Objectives
To analyze wind turbine and weather datasets
To build a regression ML model for power prediction
To save the trained model for real-time predictions
To integrate the model with Flask web application
To provide an interactive UI for user input and output display

⭐ Key Features
Predict wind turbine power output using ML
Trained model saved in .sav format
Flask web interface for real-time prediction
Fast and accurate output generation
Easy-to-use web UI with templates
Supports dataset-based retraining

🛠️ Technology Stack
Frontend
HTML
CSS
Bootstrap
Backend
Python Flask
Machine Learning
Pandas
NumPy
Scikit-learn
Matplotlib
Model Saving
power_prediction(.sav file)
Tools Used
Jupyter Notebook
VS Code

📂 Folder Structure
Wind-Turbine-Energy-Prediction/
│
├── .ipynb_checkpoints/
│
├── data/
│   └── (dataset file if any)
│
├── Flask - Wind-Mill-Power-Prediction/
│   ├── static/
│   │   └── (css/images files)
│   │
│   ├── templates/
│   │   ├── index.html
│   │   └── result.html
│   │
│   ├── app.py
│   ├── windApp.py
│   └── power_prediction.sav
│
├── power_prediction.sav
├── test_model.py
├── wind turbine energy prediction.py
└── Wind_mill_model.ipynb

⚙️ Installation & Setup Instructions
Step 1: Open Project Folder
Open your folder in VS Code.
Step 2: Create Virtual Environment
Run this command in VS Code terminal:
python -m venv venv
Step 3: Activate Virtual Environment
For Windows:
venv\Scripts\activate
Step 4: Install Required Libraries
pip install flask numpy pandas scikit-learn matplotlib
(If you already have requirements.txt, use:)
pip install -r requirements.txt

🧠Model Training
Your ML model is trained using:
Wind_mill_model.ipynb
or
wind turbine energy prediction.py
To train using Python file:
python "wind turbine energy prediction.py"
After training, the model is saved as:
power_prediction.sav

🧪 Model Testing
To test your saved model:
python test_model.py
This will verify that the .sav model file is working properly.

🌐 Running the Flask Web Application
✅ Step 1: Go to Flask Folder
cd "Flask - Wind-Mill-Power-Prediction"
✅ Step 2: Run Flask App
python app.py
✅ Step 3: Open Browser
Go to:
http://127.0.0.1:5000/

🖥️ How to Use the Web App
Open the website in browser
Enter required weather values (wind speed, temperature, humidity, etc.)
Click Predict
The system displays predicted wind turbine energy output

📊 Output

The model gives predicted output as:
Wind Turbine Power Output
Energy production value (kW / MW)
📈 Machine Learning Workflow
Data Collection
Data Cleaning & Preprocessing
Feature Selection
Train-Test Split
Model Training (Regression Algorithm)
Model Evaluation
Model Saving (power_prediction.sav)
Flask Deployment

📌 Applications
Renewable energy forecasting
Wind farm planning
Smart energy grid management
Reducing electricity generation loss
Improving turbine performance monitoring

⚠️ Known Issues
Incorrect input values may give wrong output
Dataset imbalance may reduce accuracy
Sudden climate change affects prediction quality

🚀 Future Enhancements
Integrate Live Weather API for real-time input
Use Deep Learning (LSTM / RNN) for time series prediction
Deploy project on cloud platforms (AWS / Azure / Heroku)
Add dashboards and graphical output charts
Store predictions in database.
