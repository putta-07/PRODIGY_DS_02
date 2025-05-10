# PRODIGY_DS_02
# Titanic Survival Prediction

This notebook explores the Titanic dataset and builds a model to predict passenger survival.

## Project Overview

The sinking of the Titanic is a well-known historical event. This project aims to analyze the passenger data and identify factors that influenced survival. We'll use various data science techniques to clean, explore, and model the data.

## Dataset

The dataset used in this project is the Titanic passenger list, which includes information about each passenger, such as age, gender, class, and whether they survived. It's a popular dataset for introductory data science projects.

## Methodology

1. **Data Cleaning:** We handle missing values and convert categorical features into a suitable format for modeling.

2. **Exploratory Data Analysis (EDA):** We use visualizations and summary statistics to gain insights into the data, exploring relationships between different variables and survival.

3. **Feature Engineering:**  We create new features from existing ones to potentially improve model performance. (**Optional, you can add this if you perform feature engineering**)

4. **Model Building:** We train a machine learning model (e.g., Logistic Regression, Decision Tree) to predict passenger survival based on the available features.

5. **Model Evaluation:** We evaluate the model's performance using appropriate metrics like accuracy, precision, and recall.

## Results

The notebook presents the findings of the analysis, including key factors that influenced survival and the performance of the prediction model.

# Insights from Exploratory Data Analysis (EDA)

1. Gender was a significant factor in survival: Females had a much higher survival rate compared to males. This is evident from the Survival Count by Gender plot.
2. Passenger class played a crucial role: Passengers in higher classes (1st and 2nd) had better survival chances than those in 3rd class. The Survival Count by Passenger Class plot highlights this trend.
3. Age influenced survival: Younger passengers, especially children, had a higher likelihood of survival. The Age Distribution by Survival plot shows the age distribution for survivors and non-survivors.
4. Fare and passenger class were correlated: The box plot of Fare by Passenger Class shows that passengers in higher classes generally paid higher fares, indicating a correlation between these variables. This aligns with the observation that higher-class passengers had a better survival rate.
5. Correlation between features: The correlation heatmap reveals relationships between numerical features, such as a negative correlation between Pclass and Fare (as mentioned above) and Pclass and Age (indicating younger passengers were more likely to be in higher classes).
# Overall Insights:

1. Socio-economic status: Passengers with higher socio-economic status (indicated by higher class and fare) had a greater chance of survival. This suggests that access to resources and privileges played a role in survival.
2. Women and children first: The analysis supports the historical account that women and children were given priority during the evacuation, leading to their higher survival rates.
3. Age as a factor: Younger individuals, particularly children, were more likely to survive, possibly due to being prioritized or having better physical resilience

## Usage

1. Clone this repository.
2. Open the `Titanic_Survival_Prediction.ipynb` notebook in Google Colab.
3. Run the notebook cells to execute the code and view the results.

## Dependencies

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (if using machine learning models)

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.
