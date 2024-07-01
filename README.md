# **Linear Regression**

*I developed a linear regression model to predict a target variable based on a given dataset. The project was implemented in a Jupyter Notebook using Python libraries including pandas, numpy, scikit-learn, seaborn, and matplotlib.
The primary goal was to build and evaluate a linear regression model, utilizing techniques such as cross-validation and performance metrics like R² score.*

- Imported Dataset using pandas
- Cleaned and preprocessed the data by handling missing values, normalizing features, and creating new features where necessary.
- Used numpy for numerical operations and data manipulation.
  
  ---

1. **Model Building**  -- using "scikit-learn"
   ---

- Split the dataset into training and testing sets using train_test_split.

- Built a linear regression model using LinearRegression from "scikit-learn".

2. **Model Evaluation**  -- using "scikit-learn"
   ---

- Evaluated the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.

- Applied cross-validation using cross_val_score to assess the model's robustness and generalizability.

- Calculated the R² score to measure the proportion of variance explained by the model.

3. **Exploratory Data Analysis (EDA) and Visualization of Results**  -- using "matplotlib", "seaborn".
   ---

 - Conducted EDA to understand the structure and distribution of the data.

 - Used seaborn and matplotlib to generate insightful visualizations that highlight trends and patterns in the data.

 - Plotted residuals to analyze the model's error distribution.

 - Created visualizations to compare model performance across different feature sets.
