 # HealthSense

HealthSense is an AI-powered health diagnosis tool built with Streamlit and machine learning. It predicts the likelihood of 11 diseases (e.g., Diabetes, Heart Disease, Chronic Kidney Disease) using pre-trained models (SVM, Logistic Regression, Random Forest) and provides personalized health recommendations. The application features a modern user interface with glassmorphism design, interactive visualizations, and a symptom checker, making it an engaging tool for preliminary health insights.

## Features

- **Disease Prediction**: Predicts 11 diseases with confidence scores using SVM, Logistic Regression, and Random Forest models.
- **Symptom Checker**: Allows users to input symptoms and identify potential conditions.
- **Health Dashboard**: Displays prediction results, confidence visualizations (bar charts, gauge charts), and historical data.
- **Personalized Recommendations**: Offers tailored health advice based on prediction outcomes.
- **Modern UI**: Glassmorphism design with animations, built using Streamlit and custom CSS.
- **History Tracking**: Stores prediction history for user reference.

## Installation

Follow these steps to set up and run HealthSense locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Atul-kr07/medical-app.git
   cd medical-app
2. Install Dependencies: Ensure you have Python 3.13 installed, then install the required libraries:
   ```bash
   pip install streamlit scikit-learn pandas numpy plotly streamlit-option-menu
3. Run the Application:
   ```bash
   streamlit run app.py
4. Access the App**: Open your browser and go to http://localhost:8501

## Usage

- **Diagnosis**: Select a disease (e.g., Diabetes), enter patient data (e.g., Glucose, BMI), and click "Predict Now" to view results.
- **Symptom Checker**: Input symptoms to identify potential conditions.
- **Health Dashboard**: View prediction history, confidence charts, and health recommendations.
- **History**: Review past predictions with timestamps.
- **About**: Learn more about the project and its purpose.

## Project Structure
   ```bash
   medical-app/
│
├── app.py                  # Main application file
├── Models/                 # Directory for pre-trained model files (.sav)
├── logo.png                # Custom logo (optional)
├── screenshots/            # Directory for screenshots (optional)
├── .gitignore              # Git ignore file
└── README.md               # Project documentation.
   ```

## System Architecture

- **User Interface (Frontend)**: Built with Streamlit, featuring a sidebar menu, disease selection, input fields, and Plotly visualizations.
- **Processing Layer**: Handles predictions using scikit-learn models and generates recommendations with custom logic.
- **Data Layer**: Stores pre-trained models (.sav files) and manages in-memory session state for history tracking.

## Technologies Used

- **Python 3.13**: Core programming language.
- **Streamlit**: Framework for building the web application.
- **Scikit-learn**: For machine learning model predictions.
- **Pandas & NumPy**: Data manipulation and processing.
- **Plotly**: Interactive visualizations.
- **Streamlit Option Menu**: Custom sidebar navigation.

## Disclaimer

HealthSense is intended for educational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Always consult a healthcare professional for accurate diagnosis and medical guidance.

## Contact

For questions or feedback, reach out to iiiatulll007@gmail.com
