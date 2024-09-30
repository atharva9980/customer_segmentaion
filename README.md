# Mall Customers Segmentation Using K-Means Clustering

This project performs customer segmentation using the K-Means clustering algorithm. The dataset contains data on mall customers, including their annual income and spending score, which is used to segment the customers into different groups based on their purchasing behavior.

## Project Overview

The project demonstrates:
- Data preprocessing and cleaning.
- Identifying the optimal number of clusters using the Elbow method.
- Training the K-Means clustering model on the customer data.
- Visualizing the clusters along with the centroids.

## Dataset

The dataset used for this project is the **Mall Customers dataset** which contains the following columns:
- **CustomerID**: Unique ID assigned to each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income**: The annual income of the customer in thousands of dollars.
- **Spending Score**: A score assigned by the mall based on customer behavior and spending habits.

### Dataset Source

The dataset is stored in `Mall_Customers.csv`. You can find it in the `Downloads` folder, or you can add it to your project directory.

## Project Dependencies

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

Install the necessary packages with the following command:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
