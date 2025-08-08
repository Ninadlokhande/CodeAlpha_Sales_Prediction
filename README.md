# Sales Prediction with Python

## Project Overview

For my **CodeAlpha** data science internship, I developed a machine learning model to predict future product sales. The model uses advertising expenditure on different platforms (TV, Radio, Newspaper) as input features to forecast sales revenue.

## Dataset

The dataset used for this project contains advertising budget information for 200 different markets. The key features are:
* TV Advertising Budget ($)
* Radio Advertising Budget ($)
* Newspaper Advertising Budget ($)
* Sales (the target variable) ($)



## Methodology

1.  **Data Exploration**: Loaded the data and performed EDA to understand the relationship between each advertising channel and sales. I used scatter plots and a correlation heatmap.
2.  **Model Building**: I chose a **Linear Regression** model because the relationship between ad spending and sales appeared to be linear.
3.  **Training & Testing**: The data was split into training and testing sets. The model was trained on the training data to learn the coefficients for each feature.
4.  **Model Evaluation**: The model's performance was evaluated on the test set using metrics like **R-squared** and **Mean Squared Error (MSE)**.

## Results

The analysis showed that **TV advertising** has the strongest positive correlation with sales. The trained regression model was able to predict sales with a high degree of accuracy, achieving an R-squared value of **[Your R-squared Score, e.g., 0.89]**. This means the model can explain **[e.g., 89%]** of the variance in sales based on advertising spend.

## How to Run

1.  Clone this repository.
2.  Ensure you have Python, Jupyter Notebook, Pandas, and Scikit-learn installed.
3.  Open the `Sales_Prediction.ipynb` file in Jupyter Notebook and run the cells.
