# K-Means Clustering for Customer Segmentation
This is a plain simple Python script utilizes the K-Means clustering algorithm for customer segmentation based on their annual income and spending behavior. The dataset used for this analysis is named "Mall_Customers.csv."

Libraries Used
Pandas: Data manipulation and analysis
NumPy: Numerical operations
Matplotlib: Data visualization
Seaborn: Statistical data visualization
Dataset
The dataset is loaded using Pandas from the file "Mall_Customers.csv" and initially explored with functions like head(), shape, isnull().sum(), and info().

Clustering Process
The analysis focuses on two features: Annual Income and Spending.
The Elbow method is employed to determine the optimal number of clusters (k) for K-Means.
K-Means clustering is performed, and the resulting clusters are visualized using a scatter plot.
Visualization
The script produces a scatter plot where each point represents a customer. The points are color-coded based on the assigned cluster, and cluster centroids are marked in purple. The script utilizes Matplotlib for plotting.

Usage
Ensure you have the required libraries installed (pip install pandas numpy matplotlib seaborn scikit-learn).
Adjust the file path in the pd.read_csv() to point to your dataset.
Run the script to see the K-Means clustering visualization.
Feel free to explore and modify the script for your specific datasets or analysis requirements.



