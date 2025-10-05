## 🗺️ Restaurant Perceptual Mapping & Competitive Positioning
Advanced MDS analysis to map competitive landscape and identify strategic positioning opportunities
---

**📊 Project Overview**
This project uses Multidimensional Scaling (MDS) and Unfolding Analysis to create perceptual maps of 12 competing restaurants, revealing how customers perceive brands across key dining attributes and identifying optimal positioning strategies for Ti Amo restaurant.
---

**🎯 Business Objective**
Map the competitive restaurant landscape to:
- Understand how Ti Amo is positioned relative to 11 competitors
- Identify customer segments with unmet needs
- Develop data-driven repositioning strategy
- Optimize pricing, atmosphere, and target demographics

---

**🔬 Methodology**
**Data Sources**
- Restaurant Attributes: Location, Food Quality, Price, Atmosphere, Seating, Libations, Parking (7 dimensions)
- Customer Preferences: 30 customers rating 12 restaurants
- Customer Demographics: Income, age, gender, number of children, race

**Analytical Approach**
**1. Unfolding Analysis - Model Selection**

Tested four configurations to find optimal representation:
- Interval Scaling vs Ordinal Scaling
- Row Conditionality vs Matrix Conditionality

Optimal Model: Ordinal Scaling with Row Conditionality
- Stress value: 0.00596 (lowest across all models)
- Iterations: 10,000
- Validation: Shepard diagram shows excellent fit (points tightly on line)

**2. Tie Handling**

Used ties="secondary" specification for customers with identical ratings (e.g., Customer 4 rated Mildred's and Shoney's both 6.5)

Secondary specification produced lower stress due to additional constraints
Better handling of ordinal relationships

**3. Stress Decomposition Analysis**

Identified restaurants contributing most/least alignment:

- High stress (misaligned): Emiliano's, Leo's 706
- Low stress (well-aligned): Paramount Grill, Shoney's

----

**💡 Key Findings**
**Restaurant Clustering**
Three natural competitive groups emerged:
**Premium Tier** (High food quality + location, Dimension 1)

Paramount Grill
The Top
Mildred's
Emiliano's

**Value Tier **(Affordability + parking, Dimension 2)

Carrabbas
Las Margaritas
Shoney's

**Balanced Tier** (Moderate across dimensions)

Beef O'Bradys
Bistro 1245
The Swamp

**Ti Amo's Competitive Position**
Current Strengths:

High scores on Atmosphere (5/7)
Strong Libations (5/7)
Good Location (3/7)

**Positioned near: Customers 22, 9, and Sub-cluster (23, 30, 20, 16)**
**Customer Segmentation
Three Major Clusters:**
- Cluster 1: Fewer children, middle-to-high income, younger, high atmosphere preference
- Cluster 2: High income, fewer children, high spending, strong atmosphere emphasis
- Cluster 3: Low income, more children, younger, lower atmosphere priority
**High-Value Sub-Clusters:**
**Sub-cluster (23, 30, 20, 16) - PRIMARY TARGET**

Income up to** $125,000**
Few/no children (0-1)
High food quality importance (9-11/scale)
High atmosphere & seating importance
Not price-sensitive
**Prefer premium dining experiences**

Sub-cluster (3, 15, 13)

Younger age
Middle-to-upper income
Distinct preferences

**Customer Insights: Mildred's & Bistro 1245 Example**
Customers 16, 20, 23, 30 cluster near these restaurants because:

**Mildred's: **High price (7), high food (7), good parking (6), premium positioning
**Bistro 1245:** Balanced excellence - food (4), atmosphere (3), seating (7), libations (7)
**Shared appeal:** Premium quality, comfortable seating, upscale ambiance
**Customer priorities:** Food quality > price, sophisticated experience valued

**Outlier: Customer 11**

Not positioned near any restaurant
Extreme and varied ratings (9-12 for some attributes, 1-4 for others)
Unique/unrealistic expectations
Difficult to satisfy regardless of offering

---
**🎯 Strategic Recommendations for Ti Amo**
Target: Sub-cluster (23, 30, 20, 16)
Repositioning Strategy:
**1. Enhance Atmosphere**

Modern, stylish décor upgrades
Improved lighting design
Private dining areas
Elegant table settings
Curated background music
Sophisticated environment matching high-income expectations

**2. Pricing Optimization**

Moderate price increases justified by quality improvements
Tiered menu structure:

Premium selections (signature dishes, wine pairings)
Core offerings (elevated classics)
Strategic pricing communicates luxury positioning



**3. Adult-Oriented Positioning**
**Eliminate family-focused elements (no kids' menu, play areas)**
Market as destination for:

Date nights
Business dinners
Sophisticated social gatherings


Exclusive couples/small group promotions
Privacy-focused seating arrangements
 
**4. Product/Service Enhancements**

Premium ingredients with refined presentation
Expanded wine/cocktail program
Attentive but unobtrusive service
Exclusive experiences (chef's table, tastings)

--- 
**📈 Visualization Highlights**
**Perceptual Maps Created:**

Combined restaurant-customer preference map (Figure 9)
Demographic overlays: Gender, Age, Income, Race, Children (Figures 10-15)
PCA biplot of restaurant attributes (Figure 16)
Restaurant preference map with attribute vectors (Figure 17)

**Joint Configuration Plots show:**
Restaurant positioning across two dimensions (42.6% and 21.7% variance explained)
Customer ideal points overlaid on restaurant positions
Clear clustering patterns
Ti Amo's current vs. optimal position

---

**🧰 Technical Skills Demonstrated**
**Advanced Techniques:**

Multidimensional Scaling (MDS)
Unfolding Analysis (4 model types compared)
Stress optimization and validation
Shepard diagram interpretation
Stress decomposition analysis
PCA for attribute visualization
Demographic profiling and overlay mapping

**Model Validation:**

Comparative stress analysis across models
Non-degenerate solution verification
Shepard diagram goodness-of-fit assessment
Stress decomposition by restaurant and customer
Treatment of tied rankings

**Tools: R (smacof, ggplot2, factoextra, dplyr)**

---

**📊 Expected Business Impact**
**Revenue Opportunity:**

Target segment represents customers with $125K income
High frequency potential (above-average dining rates)
Price insensitivity allows premium pricing strategy
Larger party sizes increase per-visit revenue

**Positioning Advantages:**

Clear differentiation from value competitors
Alignment with affluent, childless demographic trend
Premium tier positioning with Paramount/The Top/Mildred's
Stronger brand equity and customer loyalty

**Risks Addressed:**

Competitive saturation in value tier avoided
Clear target avoids "stuck in the middle" positioning
Demographic analysis reduces execution uncertainty

----
**📁 Project Deliverables**

19-page comprehensive analysis report
Multiple perceptual maps with demographic overlays
Stress comparison tables across 4 model types
R code for MDS, unfolding, and visualization
Strategic recommendations with implementation roadmap

---
✍️ Author
Anni Liu
| Univeristy of Florida | Customer Analysis | Instructor: Dr. Alan Cook | Feburary 2025 

Analytical Leadership: Advanced perceptual mapping, competitive analysis, strategic positioning

_Transforming spatial preference data into actionable competitive strategy_
