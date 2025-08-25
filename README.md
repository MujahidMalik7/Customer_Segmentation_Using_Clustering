# 🛒 Customer Segmentation Using Clustering  

## 📌 Project Overview  
This project applies **unsupervised machine learning** techniques to segment customers from the [Mall Customer Segmentation dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python).  
The goal is to group customers based on their **demographics** and **spending behavior**, enabling businesses to design **targeted marketing strategies**.  

---

## 🎯 Objectives  
- Perform **Exploratory Data Analysis (EDA)** to understand customer demographics.  
- Apply **feature scaling** for clustering.  
- Use **K-Means** and **Hierarchical Clustering** to identify customer segments.  
- Determine optimal cluster count with **Elbow & Silhouette methods**.  
- Visualize clusters using **PCA (2D reduction)**.  
- Generate **business insights** for each customer segment.  

---

## 📊 Dataset  
- **Name:** Mall Customer Segmentation Data  
- **Source:** [Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- **Attributes:**  
  - `CustomerID`  
  - `Gender`  
  - `Age`  
  - `Annual Income (k$)`  
  - `Spending Score (1-100)`  

---

## 🛠️ Tools & Libraries  
- Python 🐍  
- **pandas, numpy** → Data manipulation  
- **scikit-learn** → K-Means, Hierarchical Clustering, PCA, scaling  
- **matplotlib** → Data visualization  
- **scipy** → Dendrogram (hierarchical clustering)  

---

## 📈 Key Steps  
1. **EDA & Preprocessing** – Checked distributions, handled scaling.  
2. **K-Means Clustering** – Used inertia & silhouette to find best K.  
3. **Hierarchical Clustering** – Compared results with Ward linkage.  
4. **Visualization** – Plotted Elbow Curve, Silhouette Scores, Dendrogram, and PCA 2D cluster plots.  
5. **Cluster Profiling** – Summarized demographic and spending patterns in each group.  
6. **Business Insights** – Labeled clusters as *VIPs, Upsell Potential, Value Seekers, Budget-Conscious, Standard Shoppers*.  

---

## 💡 Business Insights
The clustering revealed distinct customer groups:  

- **VIP Customers** (High Income, High Spending) → Target with premium services & loyalty programs.  
- **Upsell Potential** (High Income, Low Spending) → Personalize offers to increase spending.  
- **Value Seekers** (Low Income, High Spending) → Attract with seasonal discounts and deals.  
- **Budget-Conscious** (Low Income, Low Spending) → Offer affordable products & entry-level services.  
- **Standard Shoppers** (Average Income & Spending) → Maintain engagement with balanced offers.  

This allows businesses to:  
✔ Improve targeted marketing  
✔ Enhance customer retention  
✔ Maximize revenue opportunities  

---

## 🔮 Future Work
- Test clustering with advanced algorithms like **DBSCAN** or **Gaussian Mixture Models (GMM)**.  
- Deploy segmentation results into a **Streamlit dashboard** for interactive exploration.  
- Integrate real-time customer data for **dynamic segmentation**.  

---

## 🏷️ Tags
`#MachineLearning` `#DataScience` `#CustomerSegmentation` `#Clustering` `#UnsupervisedLearning` `#KMeans` `#HierarchicalClustering` `#BusinessInsights`  
