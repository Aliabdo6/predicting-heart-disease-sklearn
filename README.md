# Heart Disease Prediction using Machine Learning

## Project Overview

This project aims to introduce foundational machine learning and data science concepts by exploring the problem of heart disease classification. It serves as an end-to-end example of what a data science and machine learning proof of concept might look like.

## Table of Contents

- [Project Overview](#project-overview)
- [What is Classification?](#what-is-classification)
- [Project Workflow](#project-workflow)
- [Data](#data)
- [Evaluation](#evaluation)
- [Features](#features)
- [Tools and Libraries](#tools-and-libraries)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## What is Classification?

Classification involves deciding whether a sample is part of one class or another (single-class classification). If there are multiple class options, it's referred to as multi-class classification.

## Project Workflow

1. **Problem Definition:** 
   - Binary classification to predict if a patient has heart disease based on clinical parameters.

2. **Data:**
   - Sourced from the Cleveland database at UCI Machine Learning Repository, formatted from Kaggle.
   - Uses 14 attributes out of 76.

3. **Exploratory Data Analysis (EDA):**
   - Understanding the dataset and uncovering insights.

4. **Model Training:**
   - Training various machine learning models to predict heart disease.

5. **Model Evaluation:**
   - Evaluating the models using problem-specific metrics.

6. **Model Comparison:**
   - Comparing different models to find the best one.

7. **Model Fine-Tuning:**
   - Improving the chosen model's performance.

8. **Feature Importance:**
   - Identifying which features are most indicative of heart disease.

9. **Cross-Validation:**
   - Ensuring the model performs well on unseen data.

10. **Reporting Findings:**
    - Presenting the results in an understandable format.

## Data

- The dataset contains 14 attributes which include age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise induced angina, ST depression induced by exercise relative to rest, the slope of the peak exercise ST segment, the number of major vessels colored by fluoroscopy, and thalium stress result.
- The target variable is whether or not the patient has heart disease.

## Evaluation

- The evaluation metric is to achieve at least 95% accuracy in predicting heart disease during the proof of concept.

## Features

- **age** - age in years
- **sex** - (1 = male; 0 = female)
- **cp** - chest pain type
  - 0: Typical angina: chest pain related decrease blood supply to the heart
  - 1: Atypical angina: chest pain not related to heart
  - 2: Non-anginal pain: typically esophageal spasms (non-heart related)
  - 3: Asymptomatic: chest pain not showing signs of disease
- **trestbps** - resting blood pressure (in mm Hg on admission to the hospital)
- **chol** - serum cholesterol in mg/dl
- **fbs** - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- **restecg** - resting electrocardiographic results
- **thalach** - maximum heart rate achieved
- **exang** - exercise induced angina (1 = yes; 0 = no)
- **oldpeak** - ST depression induced by exercise relative to rest
- **slope** - the slope of the peak exercise ST segment
- **ca** - number of major vessels (0-3) colored by fluoroscopy
- **thal** - thalium stress result
- **target** - have disease or not (1=yes, 0=no)

## Tools and Libraries

- **pandas** for data analysis
- **NumPy** for numerical operations
- **Matplotlib/seaborn** for plotting and data visualization
- **Scikit-Learn** for machine learning modeling and evaluation

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/heart-disease-prediction.git
    cd heart-disease-prediction
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

2. Open `heart_disease_prediction.ipynb` and follow the steps to explore the data, train the model, and evaluate the results.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.


