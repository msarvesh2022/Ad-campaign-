# Social Media Ad Campaign Performance Analysis


### Context 
A fast-food chain plans to add a new item to its menu. However, they are still undecided between three possible marketing campaigns for promoting the new product. In order to determine which promotion has the greatest effect on sales, the new item is introduced at locations in several randomly selected markets. A different promotion is used at each location, and the weekly sales of the new item are recorded for the first four weeks
## Project Overview
This project focuses on analyzing the performance of different social media ad campaigns to identify which campaign delivers the best results. Using statistical analysis and hypothesis testing, the goal was to determine if there are significant differences in performance among the campaigns.

## Objective
To compare multiple ad campaigns and identify the best-performing one using **ANOVA (Analysis of Variance)**.

## Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, SciPy/Statsmodels)
- **Excel** (for data cleaning and initial exploration)
- **Jupyter Notebook** (for analysis and visualization)

## Methodology
1. **Data Collection & Cleaning**  
   Gathered social media ad campaign data and performed preprocessing to handle missing values and ensure consistency.
   
2. **Exploratory Data Analysis (EDA)**  
   - Visualized impressions, clicks, conversions, and cost metrics.  
   - Compared descriptive statistics across campaigns.  

3. **Hypothesis Testing using ANOVA**  
   - **Null Hypothesis (H0):** There is no significant difference in performance between the campaigns.  
   - **Alternative Hypothesis (H1):** At least one campaign performs significantly better than the others.  
   - Conducted **One-Way ANOVA** test on campaign performance metrics.  

4. **Post-Hoc Analysis (if required)**  
   Tukey’s HSD test was used to identify which specific campaign outperformed others.

## Results
- ANOVA results showed **statistically significant differences** between the campaigns.  
- **Campaign 2** demonstrated better performance compared to others, with higher engagement and conversion rates.  

## Impact
By identifying the best-performing campaign, marketing teams can:  
- Optimize ad spend.  
- Focus resources on high-performing creatives.  
- Improve overall ROI of social media campaigns.  

## Key Insights
- Not all ad campaigns perform equally well.  
- Statistical testing provides confidence in decision-making.  
- Data-driven approach helps reduce marketing costs and maximize effectiveness.  

## Future Scope
- Apply **A/B testing** for future ad variations.  
- Incorporate **time-series analysis** to track performance trends.  
- Use **machine learning models** to predict campaign success.  

---

