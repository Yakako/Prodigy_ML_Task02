# Prodigy_ML_Task02
# Customer Segmentation Using K-Means Clustering

## Overview
This project applies **K-Means clustering** to segment customers of a retail store based on their **purchase behavior**. Customer segmentation helps businesses understand their customers better and enables **targeted marketing, personalized offers, and improved customer satisfaction**.

The clustering is based on the **Mall Customer dataset**, including features like **Age, Gender, Annual Income, and Spending Score**.

---

## Dataset
**Source:** [Kaggle Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  

**Columns:**
- `CustomerID` → Unique customer identifier  
- `Gender` → Male / Female  
- `Age` → Customer age  
- `Annual Income (k$)` → Income in $1000s  
- `Spending Score (1-100)` → Score assigned by the mall based on spending behavior  

---

## Preprocessing
- Dropped `CustomerID` as it is not relevant for clustering  
- Encoded `Gender` as numeric (Male = 0, Female = 1)  
- Standardized numerical features for K-Means algorithm  

---

## Methodology
1. **Determine Optimal Clusters:**  
   - Used the **Elbow Method** to identify the ideal number of clusters (commonly 3–5).  

2. **Train K-Means Model:**  
   - Clustering customers based on `Age`, `Gender`, `Annual Income`, and `Spending Score`.  

3. **Analyze Clusters:**  
   - Examined cluster distribution and centroids to understand different customer segments.  

4. **Visualize Clusters:**  
   - Scatter plots for **Annual Income vs Spending Score**  
   - Optional: 3D visualization using Age, Income, and Spending Score  

---
## License
This project is open-source and free to use under the MIT License

---
## Author
- PRUONH KIMLIYA
- Email: kimliyapruonh@gmail.com
---

## References
Kaggle Dataset: Customer Segmentation Tutorial in Python
