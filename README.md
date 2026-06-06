# Global Geopolitical Stability and Investment Attractiveness Analysis (2020–2025)

## Introduction

Investments are generally made when a nation is politically, economically, and socially stable. However, instability arising from military conflicts, violence, social unrest, economic crises, geopolitical tensions, or wars can significantly affect investor confidence and reduce the willingness of businesses to enter a market.

This project analyzes geopolitical stability and investment attractiveness using the **Global Geopolitical Conflict Dataset (2020–2025)**.

Dataset Source:

https://www.kaggle.com/datasets/muhammadhussnain09/global-geopolitical-conflict-dataset-20202025

The analysis is performed entirely using Python and focuses on understanding how economic, political, social, security, and geopolitical indicators influence a nation's stability and investment potential.

The study follows a data-driven approach, relying solely on the information available within the dataset.

---

# Objectives

The project attempts to answer the following research questions:

1. Which indicators are the strongest predictors of conflict escalation?
2. Do protests act as early warning signals?
3. Does inflation lead to instability?
4. Are sanctions associated with increased unrest?
5. Do election periods increase conflict risk?
6. Which regions are most vulnerable?
7. Can social media sentiment predict real-world instability?
8. What country profiles are most susceptible to escalation?
9. How far in advance can escalation be detected?
10. Can a machine-learning model identify high-risk countries before conflict occurs?
11. What does the global political instability landscape look like?
12. Which countries are the most attractive for investment?

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Folium
- Plotly

---

# Methodology

The analysis was conducted using the following approaches:

- Correlation Analysis
- Regression Analysis
- K-Means Clustering
- Regional Vulnerability Assessment
- Feature Importance Analysis
- Random Forest Classification
- Geospatial Visualization
- Investment Attractiveness Scoring

---

# Insight 1: Which Indicators Are the Strongest Predictors of Conflict Escalation?

The analysis revealed that:

- High instability scores
- Increased protest events
- Higher rolling protest averages

are strongly associated with conflict escalation.

These factors indicate rising civil unrest, making nations less attractive for investment due to increased uncertainty and operational risks.

---

# Insight 2: Do Protests Act as Early Warning Signals?

A correlation analysis was performed between protest activity and conflict escalation.

### Findings

| Conflict Escalation Status | Average Protest Events |
|---------------------------|------------------------|
| No Escalation | 3.27 |
| Escalation Present | 7.99 |

The results suggest that protest activity can serve as an early warning signal of future instability and conflict.

For investors, increasing protest activity may indicate rising political risk.

---

# Insight 3: Does Inflation Lead to Instability?


A regression analysis demonstrated a positive relationship between inflation and instability.

### Key Observations

- Higher inflation generally corresponds to higher instability.
- Some nations experience high protest activity despite low inflation.

This suggests that factors such as governance quality, political ideology, and social dynamics can also contribute significantly to unrest.

Investors should therefore evaluate societal conditions alongside economic indicators.

---

# Insight 4: Are Sanctions Associated with Increased Unrest?

The boxplot analysis revealed:

- The lower quartile of sanctioned nations starts near the median instability score of non-sanctioned nations.
- Approximately 75% of sanctioned countries exhibit higher instability than the lower half of non-sanctioned countries.

Examples include:

- Venezuela
- Iran

These findings suggest that sanctions often coincide with increased instability and social unrest.

---

# Insight 5: Do Election Periods Increase Conflict Risk?


The results provide limited evidence that elections directly increase conflict risk.

### Examples

- India conducts frequent elections while maintaining overall stability.
- Nations such as Nepal, Bangladesh, Pakistan, and the UK have experienced elevated conflict risks despite fewer election periods.

This suggests that institutional strength plays a larger role than election frequency alone.

---

# Insight 6: Which Regions Are Most Vulnerable?

The regional heatmap identified:

### Most Vulnerable Regions

1. Middle East
2. East Asia
3. Eastern Europe

### Moderate Risk Regions

- South Asia
- Western Europe

### Lower Risk Regions

- North America
- South America

The Middle East demonstrated the highest levels of instability and conflict escalation.

---

# Insight 7: Can Social Media Sentiment Predict Real-World Instability?

The regression analysis indicated a weak relationship between social media sentiment and instability.

### Findings

- Negative online sentiment alone does not significantly increase instability.
- Real-world escalation generally requires additional political, social, or economic triggers.

This suggests that social media sentiment should be considered a supplementary rather than primary indicator.

---

# Insight 8: What Country Profiles Are Most Susceptible to Escalation?


K-Means clustering was applied to identify country profiles.

### High Protest Clusters

- Taiwan
- Turkey
- United Kingdom
- United States
- Ukraine

These countries experience elevated protest activity despite relatively controlled inflation.

### Lower Protest Clusters

- Brazil
- China
- France
- Germany
- India

These nations demonstrated comparatively lower protest intensity despite inflationary pressures.

The findings suggest differing societal responses to economic and political challenges.

---

# Insight 9: How Far in Advance Can Escalation Be Detected?


The correlation analysis revealed that:

- Protest momentum
- Social media sentiment
- Inflation rates

can provide early indications of future instability.

These variables may serve as useful warning signals for governments and investors.

---

# Insight 10: Can Machine Learning Identify High-Risk Countries Before Conflict Occurs?


A Random Forest Classifier was developed to predict conflict escalation.

### Results

- Model Accuracy: 95%
- Correctly Classified Nations: 93%
- Misclassified Nations: 7%
- Conflict Escalation Probability Detection: 85%

The results indicate that machine learning can effectively identify nations at elevated risk before major conflicts occur.

---

# Insight 11: Global Political Instability Map

A geospatial visualization was created to highlight regions with elevated instability scores.

The map illustrates the geographic concentration of geopolitical risks and conflict-prone regions across the world.

---

# Insight 12: Countries with the Highest Investment Attractiveness

An Investment Attractiveness Score was developed using:

### Positive Factors

- GDP Growth
- Political Stability
- Media Freedom
- Social Media Sentiment

### Negative Factors

- Inflation
- Unemployment
- Protest Activity
- Border Disputes
- Refugee Outflows
- Conflict Escalation Risk

### Top Countries Identified

- Japan
- United Kingdom
- Brazil
- Ukraine
- Taiwan
- United States
- Spain
- India
- Italy
- France

### Practical Considerations

While the model identifies Ukraine as attractive from a quantitative perspective, ongoing conflict limits practical investment opportunities.

Similarly, Spain's political environment introduces additional uncertainty.

The most attractive long-term investment destinations appear to be:

- Japan
- Taiwan
- India
- France
- Italy
- United States

due to their combination of economic strength, workforce quality, technological capabilities, and geopolitical relevance.

---

# Conclusion

The analysis demonstrates that economic conditions, geopolitical tensions, military factors, protest activity, and political stability all play significant roles in shaping investment attractiveness.

Key findings include:

- Protest activity is a strong early warning indicator.
- Inflation contributes to instability.
- Sanctions are associated with increased unrest.
- The Middle East remains the most vulnerable region.
- Social media sentiment alone is a weak predictor.
- Machine learning models can effectively identify high-risk nations before conflict escalation occurs.

The study also highlights the growing importance of middle powers and strategically autonomous nations in attracting future investments.

Countries such as Japan, India, Taiwan, France, and Italy emerge as particularly attractive investment destinations due to their relative stability and long-term growth potential.

---

# Author
Sibankar Saha
