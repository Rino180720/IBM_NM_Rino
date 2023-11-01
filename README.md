# 7214-IBM_Project
# Problem Statement:
Implement data science
techniques to segment customers
based on their behaviour,
preferences, and
demographicattributes, enabling
businesses to personalize
marketing strategies and
enhance customer satisfaction.

# Dataset Details:
The "Mall Customers" dataset typically includes the following columns:

Customer ID: A unique identifier
for each customer.
Gender: The gender of the customer
(e.g., Male or Female).
Age: The age of the customer.
Annual Income (k$): The annual
income of the customer.
Spending Score (1-100): A score
that reflects the customer's
spending behavior, where a higher
score indicates more spending.

# Implementation steps:

1. Import necessary libraries:
   - Import essential Python libraries, including pandas, scikit-learn, and matplotlib, for data manipulation, clustering, and visualization.

2. Suppress FutureWarnings:
   - Configure the system to suppress FutureWarnings to prevent unnecessary warning messages.

3. Read the dataset:
   - Load the customer data from a CSV file located at a specified file path.
   - Use the specified encoding (ISO-8859-1) to read the data.

4. Data Exploration:
   - Display the DataFrame (`df`) to inspect the loaded data.
   - Check the data's information, including data types and missing values.
   - Display the first few rows of the dataset for a quick overview.

5. Handling Missing Values:
   - Check for missing values within the dataset.
   - Fill missing values with the mean of the respective columns.
   - Drop rows with any remaining missing values.

6. Label Encoding:
   - Apply label encoding to the 'Genre' column to convert categorical values (e.g., 'Male' and 'Female') into numerical values (e.g., 0 and 1).

7. Feature Scaling:
   - Use StandardScaler to scale the 'Annual Income (k$)' column to have a mean of 0 and a standard deviation of 1.
   - Standardization helps ensure that features with different scales contribute equally to clustering.

8. Data Splitting:
   - Split the dataset into features (X) and the target variable (y).
   - Divide the data into training and testing sets using train_test_split, with a specified test size and random seed.

9. K-Means Clustering:
   - Define the number of clusters (k) for K-Means clustering (in this case, k=5).
   - Apply K-Means clustering to the feature data (X) to segment customers into 'k' clusters.
   - Assign cluster labels to the data points.

10. Cluster Visualization:
    - Create a scatter plot to visualize the clusters.
    - Plot 'Annual Income (k$)' on the x-axis and 'Spending Score (1-100)' on the y-axis.
    - Color the data points based on their assigned clusters.
# To run the project:
1. Load the dataset and convert it
into the data frame.
2. All the preprocessing, model
training, and evaluation should be
executed next.
3. The visualization elements
should be executed next for a
better understanding of our model.
4. Presenting key findings,
insights, and recommendations
based on the Customer segments.
5. The customer segmentation
program on the given dataset is
executed successfully.
