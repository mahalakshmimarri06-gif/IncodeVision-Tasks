Crime Incident Data Analysis Project
This project focuses on the end-to-end data cleaning and feature engineering pipeline for a crime incident dataset. The goal was to transform raw, inconsistent data into a structured, model-ready format for predictive analysis.

🛠 Project Workflow
The data processing pipeline was built using Python and Pandas, covering the following key stages:

Data Cleaning: Addressed missing values across critical identifiers and categorical features, ensuring data completeness.

Standardization: Normalized text-based categorical columns to ensure consistency (e.g., standardizing weapon classifications).

Feature Engineering: Applied One-Hot Encoding (pd.get_dummies) to convert categorical variables into numerical indicators.

Data Integrity: Maintained ID column formats as strings to preserve sensitive formatting (e.g., leading zeros).

Validation: Performed final checks to ensure zero null values and consistent data types across the entire dataset.

📊 Key Results
Total Entries Processed: [Insert your number, e.g., 4910]

Data Types: Optimized numerical columns (int/float) and encoded categorical features (bool).

Quality Control: Achieved a null-free dataset ready for machine learning consumption.

Task 2: Customer Segmentation Analysis](Task_2.ipynb)
- Objective: Segment mall customers based on their annual income and spending patterns using clustering techniques.
- Methodology: - Performed exploratory data analysis.
    - Used the **Elbow Method** to determine the optimal number of clusters ($k=5$).
    - Implemented **K-Means Clustering** to identify distinct customer groups.
- Insights:The analysis identified 5 unique segments, including high-value "VIP" customers and budget-conscious segments, providing a foundation for targeted marketing strategies.

 Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Google Colab

🚀 How to Run
Ensure you have the required libraries installed: pip install pandas.

Run the Jupyter notebook [Your_Notebook_Name].ipynb in a Google Colab or local environment.

The final cleaned output is saved as final_cleaned_crime_data.csv.
