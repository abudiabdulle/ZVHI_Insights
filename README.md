# ZHVI Trend Analysis: Comprehensive Study of Minneapolis and the Midwest Region
An analysis of ZHVI trends in Minneapolis using Python and time-series data from Zillow.

## Project Overview
This repository presents an in-depth analysis of Zillow Home Value Index (ZHVI) trends across time, with a specific focus on the city of Minneapolis and its comparison to the broader Midwest region. The project aims to identify housing market trends, including peak and trough values, and to understand the evolving dynamics of housing affordability and market performance in Minneapolis relative to its peers.

## Research Goals
The project addresses the following objectives:
- Analyze housing market trends over time and identify key insights from ZHVI data.
- Compare the housing market of Minneapolis with the broader Midwest region, highlighting differences and commonalities.
- Identify the peak and trough ZHVI values in both Minneapolis and the Midwest region.
- Interpret housing affordability challenges, policy implications, and economic factors driving the trends.
- Provide visual and data-driven insights for policymakers, investors, and homeowners.

## Methodology
The analysis is structured as follows:

### 1. Data Preparation
- The ZHVI dataset is loaded, cleaned, and preprocessed to ensure accurate and reliable analysis.
- Minneapolis-specific data is filtered, while the Midwest data is aggregated for regional comparisons.

### 2. Exploratory Data Analysis (EDA)
- Key statistics and time-series visualizations are generated for both Minneapolis and the Midwest.
- Seasonal patterns, growth trends, and deviations are highlighted.

### 3. Comparative Analysis
- Minneapolis and Midwest trends are compared using average ZHVI values over time.
- Rates of change and relative differences are calculated.

### 4. Peak and Trough Analysis
- The highest (peak) and lowest (trough) ZHVI values are identified for Minneapolis and the Midwest.
- These values are visually annotated on time-series plots.
## Visualizations and Insights

### 1. Average ZHVI Over Time
![Average ZHVI Over Time](./path-to-your-file/Average%20ZHVI%20overtime.png)

- **Description**: This time-series visualization shows the growth in the average Zillow Home Value Index (ZHVI) across time.
- **Insights**:
  - **Trend**: The housing market has seen a steady upward trajectory, particularly after 2012, reflecting increased housing demand and economic growth.
  - **Significant Growth**: A sharp rise is observed post-2020, likely influenced by pandemic-era shifts in housing preferences and market dynamics.

---

### 2. ZHVI Trends: Minneapolis vs. Midwest Sub-Regions
![ZHVI Trends: Minneapolis vs. Midwest Sub-Regions](./path-to-your-file/MN%20vs%20midwest%20sub-regions.png)

- **Description**: A comparison of ZHVI trends between Minneapolis and Midwest sub-regions (East and West).
- **Insights**:
  - **Minneapolis Outperformance**: Minneapolis consistently shows higher ZHVI values compared to both East and West Midwest sub-regions.
  - **Post-2015 Divergence**: The gap between Minneapolis and the Midwest sub-regions has widened, emphasizing Minneapolis' stronger housing market growth.
  - **Affordability Indicator**: While Minneapolis demonstrates economic vibrancy, the Midwest remains a more affordable housing option.

---

### 3. Monthly Growth Rate of Average ZHVI
![Monthly Growth Rate of Average ZHVI]("C:\Users\abudi\OneDrive\Pictures\Screenshots\Monthly growth rate on Average ZHVI.png")

- **Description**: This plot captures the percentage change in ZHVI values on a monthly basis.
- **Insights**:
  - **Volatility**: Noticeable fluctuations, particularly during economic downturns (e.g., 2008 financial crisis) and during the COVID-19 pandemic.
  - **Sustained Positive Growth**: Recent years exhibit consistent positive growth rates, highlighting robust market performance.
  - **Market Resilience**: The post-2020 period underscores resilience and rapid recovery in housing markets.

---

### Summary of Visualizations
These visualizations provide critical evidence of the evolving dynamics in housing trends. They highlight Minneapolis' strong growth relative to the Midwest, the challenges in affordability, and the resilience of the housing market through economic cycles.











### 5. Result Interpretation
- Findings are contextualized using socioeconomic, geographic, and policy-related factors.
- Specific insights and actionable recommendations are drawn for stakeholders.

## Key Results

### Overall ZHVI Analysis
- **Peak ZHVI (Overall):** $284,373.37 on October 31, 2024.
- **Trough ZHVI (Overall):** $108,086.69 on January 31, 2000.
- The overall trends show significant increases in ZHVI values over the analyzed period, reflecting growing housing demand and economic shifts.

### Minneapolis
- **Peak ZHVI:** $325,482 on August 31, 2024.
- **Trough ZHVI:** $120,763 on March 31, 2000.
- Minneapolis demonstrated consistent growth in housing values, with notable surges in recent years.

### Midwest Region
- **Peak ZHVI:** $284,373 on October 31, 2024.
- **Trough ZHVI:** $108,087 on January 31, 2000.
- The Midwest region experienced slower growth compared to Minneapolis but remains a more affordable housing market.

### Comparison: Minneapolis vs. Midwest
- Minneapolis consistently outperformed the Midwest in ZHVI values, underscoring its economic vibrancy and attractiveness.
- The gap between Minneapolis and Midwest ZHVI values widened significantly post-2015, indicating a stronger market dynamic in Minneapolis.

## Interpretations and Insights

### Economic Factors
- Minneapolis' housing trends reflect its economic growth, driven by a robust job market and rising population.

### Affordability Concerns
- Rapid growth in ZHVI values has created affordability challenges, especially for first-time homebuyers in Minneapolis.

### Midwest as an Affordable Alternative
- The broader Midwest region offers more affordable housing options, appealing to price-sensitive buyers and retirees.

### Policy Implications
- Minneapolis needs targeted policy interventions, such as zoning reforms and affordable housing initiatives, to address rising costs and sustain market growth.

### Investment Opportunities
- Both Minneapolis and the Midwest present opportunities for investors. Minneapolis offers high-growth prospects, while the Midwest offers stability and affordability.

## Files in this Repository
- `ZHVI_Trend_Analysis.ipynb`: The Jupyter Notebook containing the analysis and visualizations for ZHVI trends in Minneapolis and the Midwest.
- `data.csv` (optional): Raw ZHVI data used for analysis.
- `visualizations/`: Folder containing plot images showcasing ZHVI trends, including comparative insights.
- `README.md`: This README file.

## Technologies Used
- **Python**:
  - Libraries: Pandas, Matplotlib, NumPy, Seaborn
- Jupyter Notebook for code execution and visualization.
- GitHub for project sharing and collaboration.

## How to Reproduce This Analysis
1. Clone the repository:
   ```bash
   git clone https://github.com/abudiabdulle/ZHVI_Insights.git

## Conclusion

This analysis provides a comprehensive view of housing trends in Minneapolis and the Midwest, highlighting key disparities and opportunities:

- **Minneapolis** demonstrates robust growth in housing values, reflecting its economic vibrancy and attractiveness. However, rapid increases in home values have led to significant affordability challenges, particularly for first-time homebuyers. The city's housing market is dynamic but requires targeted policy interventions, such as zoning reforms and affordable housing initiatives, to sustain growth while addressing affordability concerns.

- The **Midwest region** offers a more stable and cost-effective alternative to Minneapolis. While the growth rate of ZHVI values is slower, the region's affordability makes it appealing to price-sensitive buyers, retirees, and long-term investors.

- **Comparison Insights:** Minneapolis consistently outperforms the Midwest in housing value growth, driven by its strong job market and population growth. However, this also widens the gap in affordability, indicating the need for balanced regional housing strategies.

This project underscores the importance of using data-driven insights to inform housing policies, investment decisions, and homeowner strategies. The findings provide valuable resources for policymakers, investors, and stakeholders aiming to navigate and address challenges in the housing market.

