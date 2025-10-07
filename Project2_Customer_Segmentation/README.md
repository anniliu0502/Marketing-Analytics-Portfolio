# Restaurant Customer Segmentation Project
# Customer Segmentation Project

This project applies PCA (Principal Component Analysis) and hierarchical clustering to segment restaurant customers and develop a targeted marketing strategy.

---

## Objective
To identify distinct customer segments based on dining preferences, behaviors, and demographics to : 
- guide menu development
- service training
- pricing strategy
- marketing campaigns for a restaurant business

---

## Methods & Techniques
**Dataset 1: Psychographic Survey Analysis** <br/>
PCA (Principal Component Analysis): Reduced 15 survey questions into 4 key factors <br/>
Factor Rotation: Used varimax rotation to clarify factor interpretations <br/>
Validation: Bartlett's test (p < 0.001) and KMO test (MSA = 0.66) confirmed data suitability <br/>
Variance Explained: Four factors captured 50.7% of total variance <br/>

**Dataset 2: Customer Clustering**
Data Standardization: Normalized variables on different scales (1-5, 1-7, 1-8) <br/>
Hierarchical Clustering: Complete linkage method with Euclidean distance <br/>
Cluster Validation: <br/>
 - Silhouette analysis (average = 0.62 for 6 clusters)
 - Dendrogram analysis showing clear separation at distance = 4
 - Elbow method confirming diminishing returns after 6 clusters

 **Data Preprocessing**: Handled missing values, scaled variables, and normalized key features  <br/>
 **Exploratory Data Analysis (EDA)**: Used visualization to identify key behavioral patterns  <br/>
 **Clustering Algorithms**: <br/>
  - *K-Means Clustering* to create customer groups  
  - *Elbow Method* and *Silhouette Score* to determine the optimal number of clusters  
- **PCA (Principal Component Analysis)** for dimensionality reduction and visualization

---

## Tools
- **Language**: R
- **Visualization Tool**: Tableau 
- **Libraries**: psych, cluster, factoextra, ggplot2, dplyr
- **Analysis Type**: Factor analysis, hierarchical clustering, silhouette validation
- **Output Format**: PDF report with visualizations

---

## Key Insights
**Four Psychographic Factors Identified:**
- Food Quality & Diversity – Fresh ingredients, varied menu, specialty dishes
- Service & Atmosphere – Staff attentiveness vs. preference for privacy
- Price & Portion – Value consciousness, fair pricing expectations
- Convenience & Casualness – Accessibility, relaxed dining environment

**Six Customer Segments:**
1. Service Seekers (n=50) – Value service quality, moderate spending
2. Casual Diners (n=20) – Infrequent visits, low engagement across all dimensions
3. Social Foodies (n=60) – Atmosphere-focused, dine in large groups
**4. Luxury Gourmets (n=40, 20%) – TARGET SEGMENT – High spenders valuing premium food, ambiance, and service**
5. Selective Tasters (n=20) – Quality-focused but infrequent diners
6. Fast & Frequent (n=10) – Convenience-driven, high frequency but low spending

**Target Market Selection**
**Cluster 4: "Luxury Gourmets" selected as primary target based on:**
- Highest spending power (Avg_Cost: +1.47 above mean)
- Frequent dining habits (Lunch: +1.22, Dinner: +1.07 above average)
- High importance ratings across all quality dimensions:
    Food importance: +1.21
    Atmosphere importance: +0.79
    Service importance: +1.28
Larger party sizes (+0.69), indicating group dining and higher per-visit revenue

**Recommended Strategies:**
-  Position as luxury fine-dining destination
-  VIP membership and loyalty programs
-  Private dining and chef's table experiences
-  Premium wine pairings and exclusive menus
-  Targeted digital marketing through food critics and lifestyle influencers
-  Luxury brand collaborations
---

## Files
- `TeamProject2Part1.qmd`, `TeamProject2Part2.qmd` → Full code and analysis  
- `TeamProject2Part1.html`, `TeamProject2Part2.html` → Rendered interactive report
- `TeamProject2_6clusters.twb` → Tableau visualization 
- `Team Project 2.pdf`→ Full analysis report (19 pages), Statistical outputs and validation tests,  Correlation matrices and dendrograms, and   Cluster profiles and segment descriptions

---
### Author
**Anni Liu**  
Course: | University of Florida | Customer Analysis | Dr. Alan Cooke | February 2025

