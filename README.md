 Analyzing Food Price Patterns in Sri Lanka Using Data Mining Techniques

Overview
This project presents a comprehensive data mining analysis of Sri Lankan food prices using real-world market data. The study applies both supervised and unsupervised learning techniques to explore price behavior, identify hidden patterns, and understand regional market differences. Clustering techniques (K-Means and Hierarchical Clustering), Association Rule Mining (Apriori Algorithm), and Logistic Regression are used to analyze price trends, co-occurring commodities, and forecast price categories. Insights from this analysis support data-driven decision-making, policy planning, and understanding food affordability in Sri Lanka.

 Dataset
The project uses the "Food Prices in Sri Lanka" dataset obtained from the Humanitarian Data Exchange (HDX). It contains approximately 13,000 records of food commodities collected across various markets and regions of Sri Lanka.

Source:[Humanitarian Data Exchange (HDX)](https://data.humdata.org/group/lka)  
Format: CSV  
Coverage period: Recent years (various months per market)  
Key Variables:Country, Date, Market, Category, Commodity, Price (LKR), Unit, Currency

Project Components

 1. Data Preparation and Analysis
- Data cleaning, handling missing values, and encoding categorical attributes
- Integration of market, commodity, and category information
- Preparation of analytical tables for clustering and modeling

 2. Clustering and Association Rule Mining
- K-Means and Hierarchical Clustering to group commodities and markets based on price similarities
- Association Rule Mining (Apriori Algorithm) to discover frequent co-occurring items and patterns

 3. Logistic Regression
- Classification of commodities into price categories (Low, Medium, High)
- Evaluation of predictive performance using confusion matrices

 4. Data Visualization
- R Shiny and Plotly used to create an interactive dashboard
- Visualizations include:
  - Commodity price distributions
  - Regional market comparisons
  - Trend analysis over time
  - Interactive filtering by commodity and region

 5. Report
- Detailed PDF report covering:
  - Data preparation and preprocessing steps
  - Analysis methodology
  - Dashboard implementation
  - Results, key findings, and recommendations

 Key Findings
- Continuous price increase for staple commodities like rice and wheat flour
- Significant regional price differences, with urban markets often higher than rural areas
- Currency fluctuations affect imported commodity prices and affordability
- Certain commodities show higher price volatility than others

 Limitations
- Dataset does not cover all markets in Sri Lanka
- Analysis is based on logged market prices, not real-time consumption
- Socio-economic factors were not included
- Findings may not fully represent current market conditions beyond dataset coverage

 Recommendations
- Focus on monitoring volatile commodities for market planning
- Policymakers can use insights for targeted subsidies and food security programs
- Use the dashboard for continuous analysis and decision support

 Challenges
- Cleaning large and inconsistent datasets
- Handling duplicate or missing data
- Designing interactive and meaningful visualizations
- Interpreting patterns across diverse markets and commodity types

 Conclusion
This project demonstrates how data mining techniques can be applied to large-scale food price datasets to uncover meaningful trends, regional disparities, and actionable insights. The interactive dashboard and analytical findings provide a robust tool for supporting policy decisions and market planning in Sri Lanka’s food economy.

 Author
Nimna Induwari  
BSc in Applied Data Science Communication (UG)  
General Sir John Kothalawala Defence University

## License
This project is for educational purposes only.
