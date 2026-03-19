# Google-Advanced-Data-Analytics-Projects
Advanced Data Analytics Python code 

Air Quality Statistical Analysis (Air_Quality_Statistical_Analysis.ipynb):
A collection of data science projects focusing on statistical analysis, data visualization, and business intelligence.
 * Objective: Analyze Carbon Monoxide levels across the US to identify significant outliers and trends.
 * Key Techniques: Log-transformation of skewed data, Z-score calculation for outlier detection, and validation using the Empirical Rule (68-95-99.7).
 * The "Gold Nugget": Successfully normalized highly skewed AQI data and identified a statistically significant outlier in West Phoenix, Arizona ($|z| > 3$).

NYC Taxi Visual Insights (NYC_Taxi_Visual_Insights.ipynb)
   * Objective: Explore and visualize New York City taxi trip data to uncover patterns in trip durations, pricing, and vendor performance.
   * Key Techniques:
       * Data Cleaning: Handled missing values and removed redundant columns (e.g., "Unnamed: 0") to ensure data integrity.
       * Exploratory Data Analysis (EDA): Performed comprehensive EDA to understand distribution of trip costs and passenger counts.
       * Advanced Visualization: Leveraged Seaborn and Matplotlib to create density plots and boxplots for outlier detection.
   * The "Gold Nugget": Used distribution plots to identify peak travel times and employed boxplots to effectively visualize and isolate extreme trip duration outliers, providing a clearer picture of "typical" taxi behavior in NYC.

Unicorn Companies Business Analysis (Unicorn_Companies_Business_Analysis.ipynb)
   * Objective: Analyze a global dataset of "Unicorn" companies (startups valued at over \$1 billion) to identify trends in valuation, industry growth, and founding dates.
   * Key Techniques:
       * Descriptive Statistics: Calculated Mean, Standard Deviation, and Min/Max values for founding years to understand the historical context of unicorn growth.
       * Interactive Visualization: Utilized Plotly Express to create dynamic, interactive charts that allow for deeper exploration of the data.
       * Business Intelligence: Aggregated data by year and industry to highlight which sectors are producing the most unicorns.
   * The "Gold Nugget": Created interactive visualizations that clearly demonstrate the massive acceleration of unicorn growth over the last decade, highlighting the shift in how quickly startups reach billion-dollar valuations compared to previous generations.


 Note on Data Files
  To maintain a clean and lightweight repository, the raw .csv data files used in these projects are not included here.
   * Source: The datasets are sourced from the Google Advanced Data Analytics Professional Certificate program and public records (such as NYC Open Data).
   * Reason: Some files exceed standard GitHub size limits (e.g., the New York Taxi datasets).
   * Reproducibility: You can still view all findings, visualizations, and statistical outputs directly within the Jupyter Notebooks in this repository without needing to run the raw data.

