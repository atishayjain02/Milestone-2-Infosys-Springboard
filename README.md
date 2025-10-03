# Stress Level Prediction App 💤

**Predict stress levels based on sleep patterns, lifestyle, and health metrics using machine learning.**

---

## Table of Contents
- [Project Overview](#project-overview)  
- [Features](#features)  
- [Dataset](#dataset)  
- [Machine Learning Model](#machine-learning-model)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Demo](#demo)  
- [License](#license)  

---

## Project Overview
The **Stress Level Prediction App** predicts an individual’s stress level by analyzing sleep health, lifestyle habits, and biometric data. The application allows users to explore the dataset, visualize key factors affecting stress, and get personalized stress predictions using a trained machine learning model.

---

## Features
- **Dataset Analysis**: Explore sleep duration, quality, and lifestyle factors.  
- **Visualization**: Interactive plots for demographic, health, and activity metrics.  
- **Stress Prediction**: Input personal data to predict stress levels (1–10 scale).  
- **Health Insights**: Includes BMI, heart rate, blood pressure, physical activity, and sleep disorder analysis.  
- **Download Dataset**: Users can download the dataset for offline analysis.

---

## Dataset
The dataset consists of 400 rows and 13 columns including demographic, lifestyle, sleep, and health features.  
- **Source**: [Sleep Health and Lifestyle Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)  
- **Columns**: Gender, Age, Occupation, Sleep Duration, Quality of Sleep, Physical Activity Level, BMI Category, Heart Rate, Daily Steps, Sleep Disorder, BP High, BP Low, Stress Level  

---

## Machine Learning Model
- **Model Used**: Linear Regression  
- **Performance Metrics**:  
  - **MAPE**: 4%  
  - **RMSE**: 0.37  
  - **R²**: 97%  
- Features are scaled and categorical variables are encoded using pre-trained encoders.

---

## Installation
1. Clone the repository:  
```bash
git clone https://github.com/yourusername/stress-prediction-app.git
cd stress-prediction-app
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the app:
   ```bash
   streamlit run app.py
   ```
## Usage

Navigate through the app using the Home, Dataset, and Prediction tabs.

Explore visualizations and insights on sleep and lifestyle factors.

Input your personal data to get a predicted stress level.

## License
This project is licensed under the MIT License.

If you want, I can also **add badges, a GIF demo placeholder, and a “Technologies Used” section** to make it look like a professional portfolio-ready GitHub README. Do you want me to do that?

   

