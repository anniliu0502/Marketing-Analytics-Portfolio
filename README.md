My marketing Analytics projects using Python and R - including K-means, PCA, and KNN for Business Insights.
# 🌿 Marketing Analytics Portfolio

Hi there! 👋  
I'm Anni, a Marketing Analytics graduate passionate about turning data into actionable business insights.  
Here are selected projects demonstrating my analytical, technical, and strategic skills.

---
# 📊 Marketing Analytics Projects
🎯 Restaurant Analytics Portfolio
A collection of customer analysis projects applying statistical methods and machine learning to understand restaurant consumer behavior and optimize business strategy.
This repository contains my graduate-level marketing analytics project completed in R using **Quarto (.qmd)**.  
The analysis explores **customer behavior and segmentation** using techniques like **PCA, K-Means, and KNN** to extract business insights from marketing data.

---

## 🧩 Restuarant Project Overview
**Goal:**  
To analyze customer-level data to identify patterns, reduce dimensionality, and predict marketing outcomes for better targeting strategies.

**Project 1: Customer Segmentation Analysis**
- Focus: Identifying distinct customer groups through PCA and hierarchical clustering
- Methods & Techniques:
-  Principal Component Analysis (PCA): Reduced 15 psychographic variables into 4 interpretable factors
Factor 1: Food Quality & Diversity
Factor 2: Service & Atmosphere Preferences
Factor 3: Price & Portion Preferences
Factor 4: Convenience & Casual Atmosphere

Hierarchical Clustering: Segmented 200 customers into 6 distinct groups
Validation: Bartlett's test, KMO (MSA = 0.66), Silhouette analysis (0.62)

**Key Findings:**
- Identified "Luxury Gourmets" segment (20% of market) as high-value target
- High spenders with frequent dining habits across all quality dimensions
- Customers near Ti Amo restaurant showed high income, fewer children

**Strategic Recommendations:**
- VIP memberships and loyalty programs for high-value customers
- Premium positioning with elevated atmosphere
- Adult-oriented dining experience (private seating, refined ambiance)
- Moderate price increases justified by quality improvements
Tools: R (psych, cluster, factoextra, dplyr, ggplot2)


**Project 2: Restaurant Perceptual Mapping**
Focus: Understanding competitive positioning and customer preferences through multidimensional scaling
Methods & Techniques:
- Multidimensional Scaling (MDS): Created perceptual maps of 12 restaurants across preference dimensions
- Unfolding Analysis: Tested multiple configurations

Interval vs. Ordinal scaling
- Row vs. Matrix conditionality
- Optimal model: Ordinal Scaling with Row Conditionality (lowest stress = 0.00596)


Shepard Diagrams: Validated model fit quality
- Stress Decomposition: Identified restaurants out of alignment with consumer preferences

**Key Findings:**
**Ti Amo** positioned strongly on atmosphere, libations, and location
Three natural restaurant clusters emerged:
 - Premium group: Paramount Grill, The Top, Mildred's (high food quality + location)
 - Value group: Carrabbas, Las Margaritas, Shoney's (affordability + parking)
`- Balanced group: Beef O'Bradys, Bistro 1245, The Swamp (moderate across dimensions)

 Customer segments identified by demographics:
- High-income, fewer children cluster near premium restaurants
- Customers 16, 20, 23, 30 prioritize food quality, seating, premium ambiance
- Customer 11 has unique/mismatched preferences (no nearby restaurants)

**Strategic Recommendations for Ti Amo:**
- Target Sub-cluster (23, 30, 20, 16): High-income customers with fewer children
- Enhance atmosphere: Modern décor, improved lighting, sophisticated environment
- Increase prices moderately: Justified by premium ingredients and refined presentation
**Adult-oriented positioning:**
- Eliminate family-focused elements
- Position as ideal for date nights, business meetings, sophisticated gatherings
- Exclusive promotions for couples and small groups

Tiered pricing strategy: Premium options + some affordable selections
Demographic Insights:
- Cluster 1: Fewer children, middle-to-high income, younger, high atmosphere preference
- Cluster 2: High income, fewer children, high spending, strong atmosphere emphasis
- Cluster 3: Low income, more children, younger, lower atmosphere priority
- Sub-cluster (23,30,20,16): Incomes up to $125,000, few/no children, high profitability potential
Tools: R (smacof for MDS, ggplot2 for visualization, factoextra)

**Techniques Used:**
- 🧮 **Principal Component Analysis (PCA)** — to reduce feature complexity and visualize data structure  
- 🎯 **K-Means Clustering** — to identify distinct customer groups  
- 🤖 **K-Nearest Neighbors (KNN)** — to predict customer response or purchase behavior

**Statistical Methods:**

Principal Component Analysis (PCA)
Factor Analysis with Varimax Rotation
Hierarchical Clustering (Complete Linkage, Euclidean Distance)
Multidimensional Scaling (MDS)
Unfolding Analysis (Interval/Ordinal, Row/Matrix Conditionality)
Validation Techniques:

Bartlett's Test of Sphericity
Kaiser-Meyer-Olkin (KMO) Test
Silhouette Analysis
Stress Decomposition
Shepard Diagrams
Elbow Method for cluster determination

**Tools & Libraries:**

R: psych, cluster, factoextra, dplyr, ggplot2, smacof
Output Formats: PDF reports with comprehensive visualizations

**Analysis Types:**

Segmentation analysis
Perceptual mapping
Demographic profiling
Competitive positioning
Preference modeling

---

## 🧠 Key Insights
- PCA reduced the dataset from 15+ variables to a few key behavioral components that explained over **80% of variance**.  
- K-Means identified **4 distinct customer segments** differing by purchase frequency and engagement level.  
- KNN achieved an accuracy of **~80%** in predicting customer response.  
- Results can help tailor **targeted marketing campaigns** and **customer retention strategies**.

---

## 💡 Business Impact
Both projects demonstrate ability to:

Extract actionable insights from complex customer data
Identify high-value customer segments for targeted marketing
Optimize positioning strategy based on competitive landscape
Translate statistical findings into concrete business recommendations
Validate analytical choices using rigorous statistical tests
Balance technical rigor with practical business application  

**Key Outcomes:**

Identified 20% high-value "Luxury Gourmets" segment representing significant revenue opportunity
Mapped Ti Amo's competitive position relative to 11 competitors
Discovered underserved customer segment (customers 23,30,20,16) with $125K income potential
Provided specific, actionable strategies for atmosphere enhancement, pricing, and positioning
---

## 📈 Visualization Examples
The report includes:
- PCA scree plots showing explained variance  
- Cluster visualizations of customer segments  
- KNN confusion matrix and accuracy metrics  

---

## 💡 Business Strategy
- High-value clusters can be prioritized for loyalty programs.  
- Dormant clusters suggest re-engagement opportunities via personalized campaigns.  
- Feature reduction (via PCA) improved model interpretability and reduced noise.

---

## 📁 Repository Structure

Project 1: Customer Segmentation (19-page analysis)
Project 2: Perceptual Mapping (19-page analysis)
Full R code and statistical outputs
Comprehensive visualizations and interpretation


---

 ## ✍️ Author
Anni Liu
Marketing Analytics | R & Python | Customer Segmentation & Perceptual Mapping
_Transforming customer data into strategic business insights_
 
