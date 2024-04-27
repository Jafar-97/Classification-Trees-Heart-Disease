# Classification-Trees-Heart-Disease
A Jupyter notebook demonstrating the use of classification trees to predict heart disease from clinical data. Based on the UCI Machine Learning Repository dataset, this project applies machine learning techniques for insightful data analysis and predictive modeling.
```
# Heart Disease Prediction using Classification Trees

## Overview
This Jupyter notebook utilizes classification tree models to predict the presence of heart disease in patients. The dataset used comes from the UCI Machine Learning Repository and includes various attributes related to heart health.

## Dataset
The dataset includes the following attributes:
- Age: Age of the patient
- Sex: Sex of the patient
- CP (Chest Pain type)
- RestBP (Resting Blood Pressure in mm Hg)
- Chol (Serum Cholesterol in mg/dl)
- FBS (Fasting Blood Sugar > 120 mg/dl)
- RestECG (Resting Electrocardiographic results)
- Thalach (Maximum heart rate achieved)
- Exang (Exercise induced angina)
- Oldpeak (ST depression induced by exercise relative to rest)
- Slope (the slope of the peak exercise ST segment)
- CA (number of major vessels colored by fluoroscopy)
- Thal (Thallium heart scan results)
- HD (Diagnosis of heart disease - Target Variable)

## Features
- Data preprocessing including handling of missing data
- Exploratory data analysis
- Building a classification tree model
- Pruning the decision tree using complexity parameter
- Evaluating model performance with confusion matrix
- Visualization of the decision tree

## Installation
To run this notebook:

1. Clone the repository:
   ```bash
   git clone [repository-url]
   cd [repository-directory]
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook in Jupyter:
   ```bash
   jupyter notebook
   ```

## Requirements
The following Python libraries are needed:
- Pandas
- Numpy
- Matplotlib
- Scikit-Learn

You can install them using the following command:
```bash
pip install pandas numpy matplotlib scikit-learn
```

## Usage
Execute the notebook cells sequentially to understand the workflow and the decision-making process behind the prediction model.

## Contributing
Contributions to improve the notebook or extend the analysis are welcome. Please fork the repository and submit a pull request with your changes.

```
