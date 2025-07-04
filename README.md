# 🧠 K-Means Clustering on Mall Customers

## 📌 Objective

This project performs **unsupervised learning** using the K-Means clustering algorithm to segment mall customers based on their behavior and features such as age, income, and spending score.

---

## 🛠️ Tools & Libraries Used

- **Python**
- `Pandas` – Data loading and manipulation
- `Matplotlib` & `Seaborn` – Data visualization
- `Scikit-learn` – KMeans algorithm, PCA, and evaluation metrics

---
## 🔁 Workflow

### 1. Load and Explore Data
- Load the CSV file into a pandas DataFrame.
- Optionally drop `CustomerID` and `Gender` for numerical clustering.

### 2. Elbow Method to Choose K
- Use the Elbow Method by plotting inertia values over different `K` values.
- Helps identify the "elbow point" where adding more clusters doesn’t improve performance significantly.

### 3. K-Means Clustering
- Apply K-Means using the optimal `K` found from the elbow method (usually 5).
- Assign cluster labels to each customer.

### 4. PCA for 2D Visualization
- Use Principal Component Analysis (PCA) to reduce dimensionality to 2D.
- Visualize the customer segments using a color-coded scatter plot.

### 5. Evaluate with Silhouette Score
- Measure clustering performance using the **Silhouette Score**.
- Score closer to 1 indicates well-separated clusters.

---

## 📈 Output

- Clustered dataset with a new `Cluster` column.
- 2D visualization of customer segments.
- Elbow curve and Silhouette Score for evaluation.

---

