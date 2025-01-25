# Sampling Assignment

## Overview
This project addresses the problem of class imbalance in datasets and evaluates the performance of different sampling techniques on machine learning models. The assignment focuses on balancing the `Creditcard_data.csv` dataset, applying various sampling techniques, and analyzing their impact on model accuracy.

## Dataset
- **Name**: Credit Card Fraud Detection Dataset
- **Source**: [Creditcard_data.csv](https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv)
- **Description**: The dataset contains imbalanced classes, requiring techniques to balance the data before training machine learning models.

## Objective
1. Convert the dataset into a balanced class dataset using different sampling techniques.
2. Create five samples using a sample size detection formula.
3. Apply five different sampling techniques and train five machine learning models.
4. Evaluate the accuracy of each model with each sampling technique.
5. Determine which sampling technique gives the best accuracy for each model.

## Sampling Techniques
The following techniques were applied to balance the dataset:
1. Oversampling (SMOTE)
2. Undersampling
3. SMOTE-Tomek Links
4. Tomek Links
5. Edited Nearest Neighbors (ENN)

## Machine Learning Models
The models used in this project:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting

## Project Files
- **`sampling_assignment.py`**: Python script for data balancing, sampling, model training, and evaluation.
- **`Creditcard_data.csv`**: Dataset used for training and evaluation.
- **`sampling_results.csv`**: Results showing model accuracies for each sampling technique.
- **`discussion.md`**: Detailed discussion on results and observations.

## Results
The accuracy of each model for each sampling technique is saved in `sampling_results.csv`. The results reveal which sampling technique works best with each model.

## Instructions
1. Clone this repository:
   ```bash
   git clone <repository-link>
   ```
2. Navigate to the project directory:
   ```bash
   cd sampling-assignment
   ```
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Python script:
   ```bash
   python sampling_assignment.py
   ```
5. Review the results.

## Insights and Observations
- Oversampling and SMOTE-Tomek Links generally improved model accuracy.
- Random Forest and Gradient Boosting showed robust performance across all sampling techniques.
- Undersampling reduced accuracy due to loss of important data.

## Submission
The project is uploaded on GitHub and includes all necessary files. 

## Acknowledgements
This project utilized techniques and methods from [Analytics Vidhya's guide on class imbalance](https://www.analyticsvidhya.com/blog/2020/07/10-techniques-to-deal-with-class-imbalance-in-machine-learning/).

## Author
- **Name**: Shaambhavi Sharma 
- **Email**: shaambhavi05@gmail.com
- **GitHub**: Shaambhavi58
