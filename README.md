### README: Data Science Assignment – eCommerce Transactions Dataset  

---

#### **Overview**  
This project focuses on analyzing an eCommerce Transactions dataset consisting of three files: **Customers.csv**, **Products.csv**, and **Transactions.csv**. The objective is to perform Exploratory Data Analysis (EDA), build machine learning models, and derive actionable insights to solve real-world eCommerce challenges.  

---

#### **Files in the Dataset**  
1. **Customers.csv**: Contains customer demographic information such as CustomerID, Region, and SignupDate.  
2. **Products.csv**: Includes details about the products such as ProductID, Category, and Price.  
3. **Transactions.csv**: Tracks transaction history, including TransactionID, CustomerID, ProductID, TotalValue, and TransactionDate.  

---

#### **Tasks Completed**  

##### **Task 1: Exploratory Data Analysis (EDA)**  
- **Objective**: Analyze the dataset for trends, anomalies, and insights.  
- **Steps Taken**:  
  1. Cleaned the data by handling missing values and ensuring proper data types.  
  2. Explored customer behavior, product performance, and transaction trends.  
  3. Created visualizations such as bar plots, heatmaps, and time-series graphs to identify patterns.  
  4. Derived five actionable business insights:  
     - Identified top-performing products and categories.  
     - Analyzed customer purchasing behavior by region and signup date.  
     - Highlighted peak transaction periods.  
     - Uncovered relationships between product price and transaction value.  
     - Found clusters of customers with similar spending habits.  

---

##### **Task 2: Lookalike Model**  
- **Objective**: Recommend the top 3 similar customers for each customer based on profile and transaction history.  
- **Steps Taken**:  
  1. Merged data from all three files to create a unified dataset.  
  2. Engineered features such as total spend, unique products purchased, and transaction frequency.  
  3. Normalized the features using `StandardScaler` for similarity calculations.  
  4. Used **cosine similarity** to compute pairwise similarity scores between customers.  
  5. Generated a map of customers with their top 3 lookalikes and similarity scores.  
  6. Created a **Lookalike.csv** file for the first 20 customers (CustomerID: C0001 to C0020).  

---

##### **Task 3: Customer Segmentation (Clustering)**  
- **Objective**: Segment customers into distinct clusters based on profile and transaction data.  
- **Steps Taken**:  
  1. Combined demographic and transaction data to form customer features.  
  2. Preprocessed the data by scaling features and handling categorical variables.  
  3. Applied the **KMeans clustering algorithm** to create customer segments, experimenting with clusters between 2 and 10.  
  4. Evaluated clustering quality using metrics like the **Davies-Bouldin Index (DBI)**.  
  5. Visualized the clusters using scatter plots and heatmaps to interpret customer segments.  
  6. Delivered a report summarizing:  
     - The number of clusters.  
     - DBI score and other metrics.  
     - Business insights derived from clustering.  

---

#### **Deliverables**  
1. **EDA Report**: Summarized trends and insights with supporting visualizations.  
2. **Lookalike.csv**: Contains a map of customers and their top 3 lookalikes with similarity scores.  
3. **Clustering Report**: Includes the number of clusters, DBI score, and visualizations of customer segments.  
4. **Code Files**: Python scripts and Jupyter notebooks documenting the process for each task.  

---

#### **Tools and Libraries Used**  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Visualization**: Bar charts, scatter plots, heatmaps, and cluster plots  

---

