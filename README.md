# FixedSolutions
# Marketing-Compaign Effect on Sales Analysis

This repository contains a Jupyter Notebook (Untitled14.ipynb) that performs an analysis on the effect of advertisement on sales in a company. The notebook utilizes various libraries for data processing, visualization, and modeling.

## Installation

Before running the notebook, make sure you have the following dependencies installed:

- `dataprep`: Library for data report. Install with `pip install dataprep`.
- `phik`: Library for correlation. Install with `pip install phik`.
- `pandas`: Data manipulation library. Install with `pip install pandas`.
- `numpy`: Numerical computing library. Install with `pip install numpy`.
- `matplotlib`: Visualization library. Install with `pip install matplotlib`.
- `seaborn`: Statistical data visualization library. Install with `pip install seaborn`.
- `scikit-learn`: Machine learning library. Install with `pip install scikit-learn`.

## Objective

The objective of this analysis is to discuss the effect of advertisement on sales in the company. The notebook explores the dataset, performs feature engineering, and conducts statistical analysis to understand the relationship between advertisement and sales.

## Usage

1. Load the dataset: The notebook loads the dataset from the file "full_gen_data.csv". Make sure the file is available in the specified path or modify the code to load the dataset from a different location if needed.

2. Data Exploration: The notebook performs initial data exploration, including checking for missing values, duplicates, and unique values for each column. It generates a data report using the `dataprep` library to provide an overview of the dataset.

3. Feature Engineering: The notebook applies feature engineering techniques to create new features from existing ones. It aggregates color features, extracts information from the "sizes" feature, calculates derived features like profit margin and discount ratio, and extracts date and time features from the "retailweek" column.

4. Statistical Analysis: The notebook calculates correlation coefficients using the `phik` library and visualizes the correlation heatmap. It also analyzes the impact of promotions, gender, sizes, countries, and product groups on the acceptance of offers.

5. Visualization: The notebook generates various bar graphs to visualize the count and normalized count of offers accepted based on different factors such as promotions, gender, sizes, countries, and product groups.

6. Model Evaluation: The notebook provides a classification report for evaluating the performance of a machine learning model. It uses the `Pipeline` class from `scikit-learn` for preprocessing and the `train_test_split` function to split the data into training and testing sets. The model's performance is evaluated using precision, recall, and F1-score metrics.

## Analysis  Conclusion: T
he notebook concludes with a summary of the findings from the analysis and discusses the impact of advertisement on sales in the company.

- Increase the number of promotions: The analysis indicates that promotions have a positive impact on offer acceptance. Therefore, increasing the frequency and intensity of promotions may lead to higher acceptance rates.

- Focus on months with high offer acceptance: The months of 1, 2, 3, 6, 7, 8, 9, and 12 show a higher acceptance rate. Allocating more resources and efforts towards promotions during these months may yield better results.

However, it is important to note that the analysis was limited due to the lack of connection with the customer. The provided data description was not sufficient to extract deeper insights.
