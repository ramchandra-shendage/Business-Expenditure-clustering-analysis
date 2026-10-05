# Business-Expenditure-clustering-analysis
This project uses K-Means Clustering to group customers based on their annual income and annual spending. The goal is to see whether customers naturally form different groups based on these two characteristics.  


## Dataset

The dataset contains **200 customers** and two variables:

- `Annual_Income_Lakh` – customer's annual income in lakhs
- `Annual_Spending_Thousand` – customer's annual spending in thousands

There are no missing values in the dataset.

## Approach

The project follows these steps:

1. Loaded and explored the dataset using Pandas.
2. Examined summary statistics and the correlation between the variables.
3. Visualized the relationship between annual income and annual spending using a scatter plot.
4. Used the **Elbow Method** to calculate Within-Cluster Sum of Squares (WCSS) for different values of `K`.
5. Applied **K-Means Clustering** with `K = 3`.
6. Visualized the resulting customer groups using a scatter plot.

## Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Key Observation

The two variables show a strong positive relationship, with a correlation of approximately **0.90**. This means customers with higher annual income generally tend to have higher annual spending.

Using K-Means, the customers are divided into **3 clusters**, giving a simple view of different customer spending patterns.

## Conclusion

This project was a simple introduction to **unsupervised learning and customer segmentation** using K-Means. It helped me understand how the Elbow Method can be used to choose the number of clusters and how clustering can reveal patterns in data without predefined labels.
