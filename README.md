# Wine Quality Prediction

This project uses machine learning to predict the quality of wine based on its physicochemical attributes. The model helps in determining wine quality based on features such as acidity, sugar, alcohol content, and other chemical properties.

## Goal
The objective is to develop a machine learning model that predicts wine quality, which can be useful for winemakers, sellers, and consumers to assess wine quality based on objective measures.

## Steps Involved
- Import Libraries: Load necessary libraries such as NumPy, pandas, matplotlib, seaborn, and scikit-learn for data handling and visualization.
- Load Data: Import the wine quality dataset for analysis.
- Visualize Data: Explore data distributions and relationships using various visualization techniques.
- Preprocess Data: Clean the data by handling missing values, normalizing features, and preparing it for model training.
- Feature-Label Split: Separate features (like acidity, alcohol, pH) from the target label (wine quality).
- Train-Test Split: Divide the dataset into training and testing sets to evaluate the model's performance.
- Train Model: Use the Random Forest Classifier to train the model for quality prediction.
- Evaluate Model: Assess the model using accuracy scores and other evaluation metrics.

## Dataset
The dataset contains various wine attributes, including acidity, sugar, alcohol content, pH, and other chemical properties. You can access the dataset via:  
`DATASET_LINK = 'https://drive.google.com/file/d/1gH-42Urrty3jo5dZNplY7gvAR_AMgbTz/view?usp=sharing'`

## Model Details
- Algorithm: Random Forest Classifier
- Framework: scikit-learn
- Features: Acidity, alcohol, sugar, pH, etc.
- Evaluation: Accuracy score and other performance metrics.

## Repository Contents
- Wine_Quality_Predictor.ipynb: Jupyter notebook containing code for data preprocessing, visualization, model training, and evaluation.
- README.md: Project documentation with setup instructions and an overview of the project.
