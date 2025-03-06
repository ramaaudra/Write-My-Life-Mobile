# Write My Life

Depression has become a major concern in recent years, with approximately 20.78% of adults in the U.S. experiencing mental health issues. Many individuals are unaware of their condition, which often leads to delays in seeking help. Our project aims to develop an application that can detect depression early, helping individuals understand their mental health status and seek help sooner.

## Key Features
- **Anonymity:** The app ensures user privacy by maintaining complete anonymity. Users can freely share their thoughts without fear of judgment, as developers do not have access to their identities.
- **User-Friendly Interface:** The app is designed to be fast, intuitive, and easy to use, providing a comfortable experience for users.
- **Safe Space:** The app creates a safe environment where individuals can express their feelings freely.
- **AI-Based Depression Detection:** The app uses Artificial Intelligence (AI) to analyze text inputs and detect signs of depression.
## Technical Overview

### Machine Learning
We have developed a machine learning model using data from Kaggle. The process includes:
- **Data Preprocessing:** Cleaning and preparing the data for training.
- **Model Training:** Using Natural Language Processing (NLP) techniques and LSTM (Long Short-Term Memory) for training the model.
- **Model Validation:** Ensuring the model performs well with validation tests.
- **Model Performance:** Achieved 91% accuracy and 10% loss.
- **Model Storage:** The trained model is saved in the H5 format, allowing it to be uploaded to our Cloud server.

### Mobile Development
The mobile application is designed with the following focus:
- **UI Design:** A smooth and clean user interface to make navigation simple and engaging.
- **API Integration:** Integrating various features and pages to ensure a seamless user experience.
- **Logical Functions:** Developing the core functionalities of the app to support operations.
- **Data Flow Management:** Managing the data flow between the app and backend services for consistent communication.
- **Text Classification:** The main feature of the app, powered by the machine learning model, which classifies text and identifies signs of depression.

### Cloud Computing
Our app relies on cloud services for model deployment and storage:
- **Google Cloud Storage:** Used to securely store the trained depression detection model.
- **Google Cloud Run:** Used to deploy the model in a serverless environment, ensuring scalability and high availability.

## Screenshot

<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
  <img src="https://github.com/ramaaudra/Write-My-Life-Mobile/blob/main/Screenshot_20241212_203349_Write%20My%20Life.jpg" width="23%" style="margin-bottom: 10px;">
  <img src="https://github.com/ramaaudra/Write-My-Life-Mobile/blob/main/Screenshot_20241212_203356_Write%20My%20Life.jpg" width="23%" style="margin-bottom: 10px;">
  <img src="https://github.com/ramaaudra/Write-My-Life-Mobile/blob/main/Screenshot_20241212_203402_Write%20My%20Life.jpg" width="23%" style="margin-bottom: 10px;">
  <img src="https://github.com/ramaaudra/Write-My-Life-Mobile/blob/main/Screenshot_20241212_203407_Write%20My%20Life.jpg" width="23%" style="margin-bottom: 10px;">
  
  <img src="https://github.com/ramaaudra/Write-My-Life-Mobile/blob/main/Screenshot_20241212_203631_Write%20My%20Life.jpg" width="23%" style="margin-bottom: 10px;">
  <img src="https://github.com/ramaaudra/Write-My-Life-Mobile/blob/main/Screenshot_20241212_204330_Write%20My%20Life.jpg" width="23%" style="margin-bottom: 10px;">
  <img src="https://github.com/ramaaudra/Write-My-Life-Mobile/blob/main/Screenshot_20241213_095943_Write%20My%20Life.jpg" width="23%" style="margin-bottom: 10px;">
  <img src="https://github.com/ramaaudra/Write-My-Life-Mobile/blob/main/Screenshot_20241213_100010_Write%20My%20Life.jpg" width="23%" style="margin-bottom: 10px;">
</div>


