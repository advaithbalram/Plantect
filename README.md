# Plantect: Integrating IoT and ML For Informed Crop Planning
The Crop Recommendation System is designed to assist farmers in making informed decisions about which crops to plant based on their soil conditions. Utilizing sensors to gather real-time data on temperature and humidity, this system employs a machine learning model to analyze and predict crop suitability.

## Key Features:
* Real-time Data Collection: Sensors gather accurate data on soil conditions.
* Data Preprocessing: Ensures the data is formatted correctly for analysis.
* Machine Learning Analysis: Uses trained Random Forest Classifier to predict the best crops for given soil conditions.
* Soil Analysis: Provides insights into soil health and crop compatibility.
* User-Friendly Interface: A mobile app delivers easy-to-understand recommendations and alternative crop options.

## File Distribution
* server -> Backend (Express.js)
* plantect_sensor -> Contains Arduino file for sending sensor data to backend through NodeMCU
* model.py -> Random Forest Model (hosted as a Flask app)
* Crop_Recommendation_Model_Building.ipynb -> Jupyter Notebook File -> Preprocessing and Model Building
* All the other files are for frontend (Flutter)

This project leverages modern technologies, including NodeMCU and DHT sensors for data collection, Express.js for the backend, and Flutter for the frontend, ensuring a seamless and robust user experience.
