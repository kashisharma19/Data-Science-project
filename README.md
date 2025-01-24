# Data-Science-project
What This Project Does  

Exploratory Data Analysis (EDA)  
- Cleans and preprocesses customer, transaction, and product data.  
- Identifies sales trends, top customers, and popular products.  
- Visualizes insights with bar charts, heatmaps, and distributions.  

Lookalike Model  
- Finds the top 3 most similar customers for the first 20 customers (C0001 - C0020).  
- Uses k-Nearest Neighbors (k-NN) for similarity measurement.  
- Outputs `Lookalike.csv` with customer recommendations and similarity scores.  

Customer Segmentation  
- Clusters customers based on spending behavior and purchase frequency.  
- Uses K-Means Clustering to create meaningful customer segments.  
- Evaluates clustering performance using the Davies-Bouldin Index.  
- Generates a scatter plot to visualize customer clusters.  

---

Datasets Used  
- Customers.csv → Contains customer profile details.  
- Products.csv → Contains product details.  
- Transactions.csv → Tracks purchase history of customers.  

---

Technologies Used  
- Python 
- Pandas, NumPy → Data processing & manipulation  
- Scikit-learn → Machine learning models  
- Matplotlib, Seaborn → Data visualization  
