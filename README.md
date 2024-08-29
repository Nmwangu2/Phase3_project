# Phase3_project
Phase-3-Project
# Predicting Hypertension Medication: A Machine Learning Approach

## Project Overview

This project aims to enhance the accuracy and effectiveness of hypertension drug prescriptions using machine learning. By leveraging a dataset of patient information, the project develops a decision tree model to recommend personalized medication for patients based on their specific features.

### Problem Statement

Healthcare providers face challenges in prescribing the correct medication and dosage for patients with hypertension. Mismanagement in drug prescriptions can lead to ineffective treatment, adverse drug reactions, and increased healthcare costs. With a vast array of antihypertensive medications and varying patient conditions, ensuring optimal prescriptions is complex and error-prone.

### Objective

To improve the precision of drug prescriptions for hypertension patients by using a decision tree model that provides personalized recommendations based on patient data and clinical guidelines.

## Dataset

The dataset used in this project was sourced from Kaggle and contains the following features for each patient:
- **Age**: Age of the patient
- **Sex**: Gender of the patient
- **Blood Pressure**: Categorized as High, Normal, or Low
- **Cholesterol**: Categorized as High or Normal
- **Drug**: The medication that each patient responded to (Drug A, Drug B, Drug C, Drug X, Drug Y)

## Methodology

1. **Data Preparation**: 
   - Cleaning and encoding categorical variables (e.g., Sex, Blood Pressure).
   - Splitting the dataset into training (70%) and testing (30%) sets.

2. **Model Training**:
   - Using a Decision Tree Classifier to train the model with the training dataset.
   - Evaluating model performance using accuracy and other classification metrics.

3. **Results Interpretation**:
   - Analyzing decision tree rules to understand the decision-making process.
   - Visualizing the importance of different features in predicting the correct drug.

## How to Run the Notebook

1. **Prerequisites**:
   - Python (version 3.6 or later)
   - Jupyter Notebook
   - Required Python libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

2. **Steps to Run**:
   - Clone this repository or download the `.ipynb` file.
   - Install the necessary Python libraries if not already installed:
     ```bash
     pip install numpy pandas matplotlib seaborn scikit-learn
     ```
   - Open the Jupyter Notebook and run each cell sequentially.

3. **Output**:
   - The notebook will output the trained decision tree model, accuracy score, and other relevant metrics.
   - Visualization of the decision tree and data correlations will also be displayed.

## Results

- The decision tree model achieved high accuracy in predicting the appropriate drug for patients based on their features.
- Key insights into the decision rules were extracted, showing how different patient characteristics influence drug prescriptions.

## Future Work

- Validate the model with larger and more diverse datasets.
- Explore other machine learning algorithms to improve prediction accuracy.
- Integrate the model into a clinical decision support system for real-time prescription recommendations.

## Contributions

This project was developed by Nancy Wangu Maina. Contributions are welcome. Please fork the repository and submit a pull request for any proposed changes or enhancements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
