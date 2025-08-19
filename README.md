# HeartDisease-Prediction
# Heart Disease Prediction

This project develops a **machine learning model to predict heart disease** using patient health data. The goal is to identify patients at risk based on clinical features, supporting early diagnosis and intervention.

## Project Overview

- Built a **supervised classification model** using **303 patient records** with **13 clinical features**.  
- Developed and evaluated **Logistic Regression** and **K-Nearest Neighbors (KNN)** models to identify key clinical risk factors.  
- Achieved **88% accuracy** and **81% sensitivity** through hyperparameter tuning and model refinement.  
- Enhanced model performance by performing **exploratory data analysis (EDA)**, handling missing values, and eliminating low-informative features.

## Dataset

The dataset includes 13 clinical features such as age, blood pressure, cholesterol levels, and lifestyle factors.  
*(If using a public dataset, you can add a link here.)*

## Methodology

1. **Data Preprocessing:** Handle missing values, normalize features, and remove low-informative columns.  
2. **Exploratory Data Analysis:** Identify trends and correlations among features.  
3. **Model Training:** Train Logistic Regression and KNN models with hyperparameter tuning.  
4. **Evaluation:** Assess models based on accuracy, sensitivity, and other relevant metrics.  

## Results

- Logistic Regression and KNN both performed well, with the **best model achieving 88% accuracy** and **81% sensitivity**.  
- Key clinical features influencing predictions were identified, providing insights into risk factors for heart disease.

## Usage

To run the project:

```bash
# Clone the repository
git clone https://github.com/your-username/HeartDisease-Prediction.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
jupyter notebook notebooks/HeartDisease_Prediction.ipynb

