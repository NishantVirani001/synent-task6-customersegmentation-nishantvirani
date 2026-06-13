# synent-task6-customersegmentation-nishantvirani

# Task 6: Customer Segmentation

## 👤 Name
Nishant Virani

## 📌 Problem Statement

The objective of this project is to segment customers based on their purchasing behavior using the K-Means clustering algorithm. Customer segmentation helps businesses understand different customer groups and develop targeted marketing strategies.


## 📊 Dataset Details

**Dataset:** Mall Customer Dataset

The dataset contains customer information, including:
- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

The data is used to group customers with similar characteristics.

## 🎯 Objective

- Perform data preprocessing.
- Select important features.
- Apply K-Means clustering.
- Visualize customer clusters.
- Generate business insights from customer segments.

## ⚙️ Approach

### 1. Data Loading
- Loaded the Mall Customer dataset.
- Explored the dataset structure.

### 2. Data Preprocessing
- Checked for missing values.
- Converted categorical data into numerical format.
- Selected relevant features.

### 3. Feature Scaling
- Standardized the data using StandardScaler.

### 4. Elbow Method
- Determined the optimal number of clusters.
- Selected K = 5 for clustering.

### 5. K-Means Clustering
- Applied the K-Means algorithm.
- Assigned customers to different clusters.

### 6. Data Visualization
- Visualized customer segments using scatter plots.
- Displayed cluster centroids.

### 7. Customer Insights
- Analyzed each customer segment.
- Generated business recommendations.

## 🛠 Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📈 Results

The K-Means algorithm successfully divided customers into five distinct groups based on annual income and spending score.

### Customer Segments

### Segment 1: High Income – High Spending
- Premium customers.
- High purchasing power.

### Segment 2: High Income – Low Spending
- Wealthy but less engaged customers.
- Potential target for promotional campaigns.

### Segment 3: Low Income – High Spending
- Frequent buyers.
- Responsive to discounts and offers.

### Segment 4: Low Income – Low Spending
- Budget-conscious customers.
- Value-oriented purchasing behavior.

### Segment 5: Medium Income – Medium Spending
- Average customers.
- Stable contributors to overall business.

## 🔑 Key Insights

- Five customer segments were successfully identified.
- Annual income and spending score are effective features for segmentation.
- Different customer groups require different marketing strategies.
- Customer segmentation helps improve customer engagement and business growth.

## 🎯 Conclusion

Customer segmentation using K-Means clustering successfully identified distinct customer groups with different spending behaviors. The analysis provides valuable insights for personalized marketing, customer retention, and business decision-making.
