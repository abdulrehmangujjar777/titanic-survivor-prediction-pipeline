# Titanic Survivor Prediction: End-to-End ML Pipeline

## Project Overview
This project implements a production-ready machine learning pipeline to predict passenger survival on the Titanic. The core objective is to demonstrate the use of the Scikit-learn Pipeline API for automated data preprocessing and model training, ensuring a clean and reproducible workflow.

## Key Features
- **Data Preprocessing**: Automated handling of missing values using Median and Most Frequent imputation strategies.
- **Feature Engineering**: Implementation of One-Hot Encoding for categorical variables and Standard Scaling for numerical features.
- **Model Architecture**: Utilization of a Random Forest Classifier to handle non-linear relationships in the dataset.
- **Advanced Evaluation**: Beyond simple accuracy, the project evaluates performance using Confusion Matrices, F1-Scores, and F-beta (F2) scores to prioritize recall.

## Repository Structure
- `taxt 2 Assigment.ipynb`: Detailed Jupyter Notebook containing step-by-step modular execution and data visualization.
- `app.py`: Streamlit web application for real-time model interaction.
- `titanic_model_pipeline.pkl`: The serialized joblib file of the complete trained pipeline.
- `train.csv`: The primary dataset used for training and validation.

## Technical Stack
- **Language**: Python
- **Libraries**: Scikit-learn, Pandas, NumPy
- **Visualization**: Seaborn, Matplotlib
- **Deployment**: Streamlit
- **Model Storage**: Joblib

## Installation and Usage
1. Clone the repository.
2. Install the required dependencies:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn streamlit joblib



