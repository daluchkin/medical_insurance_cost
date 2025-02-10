[Portfolio](https://github.com/daluchkin/data-analyst-portfolio) |  [Projects](https://github.com/daluchkin/data-analyst-portfolio/blob/main/projects.md) | [Certificates](https://github.com/daluchkin/data-analyst-portfolio/blob/main/certificates.md) | [Contacts](https://github.com/daluchkin/data-analyst-portfolio#my_contacts)


# Medical Insurance Cost Prediction

This project aims to determine the best regression model for predicting medical insurance costs based on various factors such as age, BMI, smoking status, and region. The dataset contains numerical and categorical variables, requiring appropriate preprocessing techniques before model training.

## Objective

The goal is to compare multiple regression models and identify the one that provides the most accurate predictions. The models evaluated in this project include:

+ Linear Regression
+ Ridge & Lasso Regression (Regularization)
+ Polynomial Regression
+ Support Vector Regression (SVR)
+ Decision Tree Regressor
+ Random Forest Regressor

## Project Workflow

1. Exploratory Data Analysis (EDA)
   + Visualizing feature distributions
   + Identifying correlations
   + Detecting outliers
3. Data Preprocessing
   + Handling missing values (if any)
   + Encoding categorical features
   + Feature scaling and transformation
4. Model Training & Evaluation
   + Splitting the data into training and testing sets
   + Training each model using appropriate hyperparameters
   + Evaluating performance using metrics:
     + Mean Absolute Error (MAE)
     + Mean Squared Error (MSE)
     + $R^2$ Score
6. Model Selection
   + Comparing model performance
   + Selecting the best model based on accuracy and generalization capability

## Technologies Used

+ Python (Jupyter Notebook)
+ Pandas & NumPy (Data Handling)
+ Matplotlib & Seaborn (Data Visualization)
+ Scikit-Learn (Model Training & Evaluation)

## Results & Findings

The best model is determined based on evaluation metrics. A detailed comparison of all models is provided in the notebook, along with insights into why a particular model outperformed the others.

## How to Run the Project

 1. Clone the repository:

```bash
git clone https://github.com/daluchkin/medical_insurance_cost.git
```

 2. Install dependencies:

```bash
pip install -r requirements.txt
```

 3. Open and run the Jupyter Notebook:

```bash
jupyter notebook
```

## Acknowledgements

This dataset is downloaded from [Kaggle Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance/data).

## Future Improvements

+ Hyperparameter tuning for better optimization
+ Exploring ensemble models for higher accuracy
+ Incorporating additional features to improve predictions

This project is part of my data science portfolio and showcases regression model selection for real-world applications.

Feel free to explore, contribute, or provide feedback! 

[Portfolio](https://github.com/daluchkin/data-analyst-portfolio) |  [Projects](https://github.com/daluchkin/data-analyst-portfolio/blob/main/projects.md) | [Certificates](https://github.com/daluchkin/data-analyst-portfolio/blob/main/certificates.md) | [Contacts](https://github.com/daluchkin/data-analyst-portfolio#my_contacts)
