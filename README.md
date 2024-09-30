# Boxing_prediction
Boxing Matches Analysis

Overview

This project focuses on analyzing a dataset of boxing matches, leveraging machine learning models to predict outcomes based on various characteristics of the opponents. The dataset includes features such as estimated punch power, punch resistance, rounds boxed, and knockout percentages for two opponents in each match.

Dataset
The dataset popular_matches.csv contains 152 entries with the following features:

opponent_1: Name of the first opponent

opponent_2: Name of the second opponent

opponent_1_estimated_punch_power: Punch power estimate of opponent 1

opponent_2_estimated_punch_power: Punch power estimate of opponent 2

opponent_1_estimated_punch_resistance: Resistance estimate of opponent 1

opponent_2_estimated_punch_resistance: Resistance estimate of opponent 2

opponent_1_rounds_boxed: Total rounds boxed by opponent 1

opponent_2_rounds_boxed: Total rounds boxed by opponent 2

opponent_1_round_ko_percentage: KO percentage for rounds boxed by opponent 1

opponent_2_round_ko_percentage: KO percentage for rounds boxed by opponent 2

opponent_1_has_been_ko_percentage: Percentage of times opponent 1 has been knocked out

opponent_2_has_been_ko_percentage: Percentage of times opponent 2 has been knocked out

opponent_1_avg_weight: Average weight of opponent 1

opponent_2_avg_weight: Average weight of opponent 2


Result: The outcome of the match






Steps in the Project

1. Data Preprocessing

Missing values are handled by dropping rows with NaN values.

Data types are adjusted to ensure consistency, especially for numeric values such as punch power and rounds boxed.
Basic exploratory data analysis (EDA) is performed to understand the distribution of data.


2. Model Building

The project uses Logistic Regression to predict the outcome of boxing matches.

Features are prepared using One-Hot Encoding where necessary.

The dataset is split into training and testing sets.


3. Model Evaluation

Accuracy score is used to evaluate the performance of the model on the test data.

Libraries Used

Pandas: For data manipulation and analysis

Seaborn: For data visualization

Matplotlib: For creating plots

NumPy: For numerical operations

Scikit-learn: For machine learning tasks like model building and evaluation

mlxtend: Additional tools for data science and machine learning


How to Run
1. Install the required Python libraries:

pip install pandas seaborn matplotlib scikit-learn mlxtend


2. Ensure you have the dataset popular_matches.csv in the correct path.


3. Run the Jupyter Notebook to perform data analysis and model training.



Results

The model is evaluated based on its accuracy in predicting match outcomes. Further improvements could involve using 

more advanced algorithms or optimizing hyperparameters tuning
