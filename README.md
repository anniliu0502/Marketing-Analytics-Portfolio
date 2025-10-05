My marketing Analytics projects using Python and R - including K-means, PCA, and KNN for Business Insights.
# 🌿 Marketing Analytics Portfolio

Hi there! 👋  
I'm Anni, a Marketing Analytics graduate passionate about turning data into actionable business insights.  
Here are selected projects demonstrating my analytical, technical, and strategic skills.

---

## 🧩 1. Customer Segmentation using K-Means Clustering
**Goal:** Identify distinct customer groups to improve targeted marketing campaigns/ giving recoomendation to the resturants to improve the business.

**Dataset:** Retail customer transactions (simulated)  
**Tools:** Python (pandas, sklearn, matplotlib, seaborn)  

**Methods:**
- Cleaned and normalized customer purchase data.
- Applied **K-Means Clustering** and used the **Elbow Method** to find optimal k.
- Visualized clusters with Seaborn scatterplots.

**Key Findings:**
- Found 4 key clusters: “High-Value Loyal”, “Frequent Low Spenders”, “Occasional Buyers”, “Dormant”.
- Cluster 1 contributed to 45% of total revenue.

**Business Insight:**
> Recommended targeted retention campaigns for Cluster 1 and cross-selling to Cluster 3.

📊 [Notebook Link](./kmeans_customer_segmentation.ipynb)

---

## 🧮 2. Dimensionality Reduction with PCA
**Goal:** Reduce complexity of customer behavior data and identify key behavioral components.  

**Tools:** R / Python (sklearn.decomposition, matplotlib)  

**Methods:**
- Applied **PCA** to compress 25 features into 5 components.
- Visualized explained variance ratio.
- Interpreted top components influencing customer satisfaction.

**Results:**
- 5 principal components explained **87% of variance**.
- “Frequency” and “Recency” metrics were strongest predictors of loyalty.

**Business Insight:**
> Simplified marketing dashboard metrics; improved decision speed for management.

📘 [Notebook Link](./pca_customer_behavior.ipynb)

---

## 🤖 3. Predicting Customer Conversion with KNN
**Goal:** Build a simple predictive model for customer conversion likelihood.  

**Tools:** Python (sklearn, pandas)  

**Methods:**
- Labeled dataset with binary “Converted / Not Converted”.
- Split data 80/20 for training and testing.
- Tuned KNN hyperparameters using GridSearchCV.

**Results:**
- Accuracy: 82% | Precision: 79% | Recall: 76%.
- Top features: click_rate, ad_duration, past_purchases.

**Business Insight:**
> Enabled marketing team to prioritize high-conversion leads and reduce ad spend by ~15%.

📙 [Notebook Link](./knn_conversion_model.ipynb)

---

## 🧭 Contact
📧 anniliu5214@email.com  
 
