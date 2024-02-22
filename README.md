# Used Car Price Prediction

## Overview:
This project aims to develop a machine learning model to predict the prices of used cars based on various features such as year of manufacture, kilometers driven, fuel type, and company. The dataset used for training and testing the model consists of information about used cars including their specifications and prices.

## Key Steps:
1. **Data Cleaning and Preprocessing**:
    - Removed irrelevant columns and cleaned the dataset by handling missing values, duplicates, and inconsistencies.
    - Preprocessed categorical variables using techniques such as encoding and transformation.

2. **Exploratory Data Analysis (EDA)**:
    - Conducted EDA to gain insights into the distribution and relationships among different features.
    - Visualized relationships between the target variable (price) and other features using plots and statistical analysis.

3. **Model Development**:
    - Applied various machine learning algorithms including linear regression to build predictive models.
    - Utilized techniques such as One-Hot Encoding and Column Transformer to handle categorical variables.
    - Evaluated model performance using metrics like R^2 score and selected the best-performing model.

4. **Train-Test Split**:
    - Split the dataset into training and testing sets to assess model generalization and avoid overfitting.

5. **Model Selection**:
    - Explored different random states for Train-Test Split to identify the model with the highest R^2 score.

6. **Deployment**:
    - Deployed the final trained model for predicting used car prices.

## Technologies Used:
- Python
- Libraries: pandas, NumPy, scikit-learn, matplotlib, seaborn

## Future Improvements:
- Implement advanced machine learning algorithms for potentially improving prediction accuracy.
- Incorporate additional features or external datasets for better model performance.
- Deploy the model as a web application for user-friendly access.

## Repository Structure:
- `data/`: Contains the dataset used for training and testing.
- `notebooks/`: Jupyter notebooks detailing the data analysis, preprocessing steps, model development, and evaluation.
- `scripts/`: Python scripts for data cleaning, preprocessing, model training, and evaluation.
- `README.md`: Markdown file providing an overview of the project, instructions for running the code, and other relevant details.
- `requirements.txt`: Text file listing all the required Python libraries and their versions.
