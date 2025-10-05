**Unsupervised Learning & Market Segmentation Analysis - PCA, K-Means Clustering, and Factor Analysis for consumer insights**

**Project Overview:** <br/>
This repository demonstrates advanced unsupervised learning techniques applied to two distinct business problems: wine quality classification through chemical properties and automotive market segmentation through psychographic profiling. The projects showcase dimensionality reduction, clustering algorithms, and interpretive factor analysis to uncover hidden patterns in consumer data. <br/>

---
**Project**
1. Wine Classification: Chemical Properties Analysis <br/>
Business Problem: Can chemical properties alone distinguish red from white wines and predict quality scores without labeled training data? <br/>
Dataset: 6,500 bottles of vinho verde wine from northern Portugal <br/>

- 11 chemical properties (fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free/total sulfur dioxide, density, pH, sulphates, alcohol)
- Wine type (red/white)
- Quality score (1-10 scale, certified panel ratings)

**Methodology:** <br/>
Step 1: Principal Component Analysis (PCA)

- Standardized all 11 chemical features
- Selected 3 principal components based on:

- Elbow method visualization
- Eigenvalue threshold (>1)
- Cumulative explained variance: 64% <br/>



**Step 2: K-Means Clustering**

- Applied K-Means with K=2 on the 3 principal components
- Evaluated cluster composition by wine type and quality

**Key Findings:** <br/>
Wine Type Separation:

- Cluster 0: 85% red wine, 15% white wine (red-dominant cluster)
- Cluster 1: 7.9% red wine, 92.1% white wine (white-dominant cluster)
- Conclusion: Chemical properties successfully distinguish wine types through unsupervised learning

**Quality Score Patterns:**

- Cluster 0: Quality scores concentrated at 5-6
- Cluster 1: Quality scores concentrated at 6-7 (slightly higher) <br/>
Cluster 1 shows higher median quality based on boxplot analysis <br/>
Unsupervised technique demonstrates capability to distinguish quality levels <br/>

Chemical Property Relationships (PCA Biplot Insights):

- Alcohol negatively correlated with density (inverse relationship)
- Free sulfur dioxide and total sulfur dioxide strongly positively correlated
- Density and sulfur dioxide uncorrelated (90-degree angle in biplot)

**Wine-Specific Patterns:**

- Red wine: Greater variation along PC2, mixed quality distribution, higher-quality wines concentrated in middle-lower region
- White wine: Greater variation along PC1, quality gradient visible (lower-quality left, higher-quality right)

----
**2. Automotive Market Segmentation: Psychographic Profiling**
Business Problem: Identify distinct customer segments in the new car market based on attitudes, preferences, and ideal price points to inform targeted marketing strategies. <br/>
Dataset: Consumer responses to psychographic survey

- 17 attitude questions (Q1-Q17) covering features, performance, style, emotions
- Ideal price point preference
- Purchase history (ignored for segmentation)

**Methodology:**  
Part A: Optimal Cluster Identification <br/>
Applied K-Means clustering with evaluation metrics:

- Within-cluster sum of squares (WCSS) elbow method
- Silhouette analysis for validation

Elbow Chart Results:

Elbow point at K=3 or K=4

Silhouette Score Comparison: <br/>

- K=3: Score = 0.407
- K=4: Score = 0.47 (selected as optimal) <br/>

Part B: Cluster Characterization
Computed cluster sizes and mean responses for each segment: <br/>

Part C: Segment Profiles <br/>
Segment 0: Trend Enthusiasts <br/>

Positive attitudes across most aspects with particularly strong interest in trendiness, fashion, and making a statement through vehicle choice. Value cars as expressions of personal style. 

Segment 1: Discontented Respondents <br/>

Generally negative perceptions across all car attributes and features. Least satisfied segment showing low engagement with both functional and emotional aspects of car ownership. <br/>

Segment 2: Price-Sensitive Critics

Highly price-conscious with critical attitudes toward most car features. Show some interest in style and trendiness (Q9-Q12) but prioritize affordability over other attributes. <br/>

Segment 3: Enthusiastic Supporters

Strong enthusiasm for functional features, quality, performance, and driving experience (Q1-Q8). Less concerned with trendiness and fashion (Q9-Q12), prioritizing substance over style. <br/>

Part D: Factor Analysis
Dimensionality Reduction Through Factor Analysis: <br/>

Applied to Q1-Q17 (excluding Ideal_Price)
Selected 3 factors based on:

Explained variance analysis
Scree plot elbow method


**Applied Varimax rotation for interpretability**

Factor Loading Matrix Results: <br/>
Factor 1: Car Features & Driving Experience (Q1-Q8)

- Performance attributes
- Functional appeal
- Technical specifications
- Driving dynamics

Factor 2: Car Style & Emotional Expression (Q9-Q14) <br/>

- Design and aesthetics
- Image orientation
- Social signaling
- Personal expression

Factor 3: Emotional/Cultural Attachment (Q15-Q17) <br/>

- Cultural resonance
- Emotional connections
- Brand loyalty
- Heritage and identity
