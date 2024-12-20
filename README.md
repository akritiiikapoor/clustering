---

## **Heart Disease Clustering Analysis**

This project implements **clustering algorithms** to analyze a **synthetic heart disease dataset**. The project applies **K-Means**, **Hierarchical**, and **Mean Shift** clustering techniques and evaluates their performance using the following metrics:  

- **Silhouette Score**
- **Calinski-Harabasz Index**
- **Davies-Bouldin Index**

![Screenshot 2024-10-21 022454](https://github.com/user-attachments/assets/5d757cb9-3dd4-498f-afaa-eb686c4f32d7)
---

### **Dataset**

The dataset contains medical attributes such as **age**, **cholesterol**, and **blood pressure**, with a **target variable** indicating the presence of **heart disease**.

---

### **Clustering Algorithms Applied**

1. **K-Means**:  
   - Clusters the data into **3 groups**.  

2. **Hierarchical (Agglomerative) Clustering**:  
   - Creates **3 clusters** for comparison.  

3. **Mean Shift**:  
   - Dynamically estimates clusters, with **custom bandwidth adjustment**.

---

### **Evaluation Metrics**

The clustering methods are evaluated based on the following performance metrics:

- **Silhouette Score**: Measures the quality of the clustering.  
- **Calinski-Harabasz Index**: Evaluates the dispersion between clusters.  
- **Davies-Bouldin Index**: Assesses the average similarity ratio of each cluster.

---

### **Results**

Each clustering method is **evaluated**, and visualizations are provided for the **2D PCA-reduced data**, allowing for an easy comparison of the clustering quality.  

---

This project provides insights into the performance of different clustering algorithms for heart disease data and helps determine the best method for such analyses. 🚀
