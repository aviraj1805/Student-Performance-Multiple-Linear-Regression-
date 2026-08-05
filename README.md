# Student Performance - Multiple Linear Regression

## Overview

This project applies multiple linear regression to predict student academic performance based on a range of study-related and lifestyle factors. The goal is to model the relationship between predictor variables and a student's Performance Index, and to evaluate how well a linear model explains that relationship.

## Dataset

The dataset (`Student_Performance.csv`) contains student records with the following features:

| Feature | Description |
|---|---|
| Hours Studied | Total number of hours spent studying |
| Previous Scores | Scores obtained in previous tests |
| Extracurricular Activities | Whether the student participates in extracurricular activities (Yes/No) |
| Sleep Hours | Average number of hours of sleep per day |
| Sample Question Papers Practiced | Number of practice papers completed |
| Performance Index | Target variable representing overall academic performance |

## Project Structure

```
.
├── Student Performance.ipynb   # Main notebook: data analysis and model building
├── Student_Performance.csv     # Dataset used for training and evaluation
└── README.md                   # Project documentation
```

## Methodology

The notebook follows a standard machine learning workflow:

1. **Data Loading and Inspection** - Importing the dataset and reviewing its structure, data types, and summary statistics.
2. **Data Preprocessing** - Handling categorical variables (e.g., encoding "Extracurricular Activities") and checking for missing or inconsistent values.
3. **Exploratory Data Analysis** - Examining relationships and correlations between features and the target variable.
4. **Model Building** - Splitting the data into training and testing sets, then fitting a multiple linear regression model using scikit-learn.
5. **Model Evaluation** - Assessing model performance using standard regression metrics such as R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

## Requirements

This project uses the following Python libraries:

```
pandas
numpy
scikit-learn
matplotlib
seaborn
```

Install dependencies with:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/aviraj1805/Student-Performance-Multiple-Linear-Regression-.git
   ```
2. Navigate into the project directory:
   ```bash
   cd Student-Performance-Multiple-Linear-Regression-
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook "Student Performance.ipynb"
   ```
4. Run the cells in order to reproduce the data analysis and model results.

## Results

The notebook trains a multiple linear regression model and reports its predictive accuracy on a held-out test set, along with relevant regression evaluation metrics. Refer to the notebook for the specific coefficients, metric values, and visualizations generated during the analysis.

## License

No license has been specified for this repository. Please contact the repository owner for usage permissions.

## Author

[aviraj1805](https://github.com/aviraj1805)
