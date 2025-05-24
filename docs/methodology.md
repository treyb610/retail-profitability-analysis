# Analysis Methodology

## Data Processing Steps

1. **Data Loading & Exploration**
   - Loaded 9,994 records from Sample Superstore dataset
   - Checked for missing values and data quality issues
   - Performed initial descriptive statistics

2. **Feature Engineering**
   - Created temporal features (Year, Month, Quarter, Season)
   - Calculated business metrics (Profit Margin, Unit Price)
   - Generated discount range categories

3. **Statistical Analysis**
   - Descriptive statistics (mean, median, std dev)
   - Five-number summaries by category
   - Correlation analysis between key variables
   - Z-score analysis for outlier detection

4. **Hypothesis Testing**
   - ANOVA tests for category differences
   - T-tests for discount impact analysis
   - Seasonal effect validation

5. **Advanced Analytics**
   - Price elasticity estimation using arc elasticity
   - RFM customer segmentation
   - Time series trend analysis

## Tools & Libraries Used

- **pandas 1.3+**: Data manipulation and analysis
- **numpy 1.21+**: Numerical computations
- **matplotlib 3.4+**: Static visualizations
- **seaborn 0.11+**: Statistical visualizations
- **scipy 1.7+**: Statistical testing

## Limitations & Assumptions

- Dataset spans 2014-2017, may not reflect current market conditions
- Price elasticity calculated using simplified arc elasticity method
- Seasonal patterns may vary by geographic location
- Customer segmentation based on available transactional data only
