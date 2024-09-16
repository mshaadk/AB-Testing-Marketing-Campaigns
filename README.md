# A/B Testing for Marketing Campaigns

This Jupyter Notebook demonstrates how to perform A/B testing to evaluate the effectiveness of two different marketing campaigns: a Control Campaign and a Test Campaign. The analysis focuses on various marketing metrics to determine which campaign performs better in terms of engagement, conversions, and overall effectiveness.

## Project Overview

In this project, we:
1. Load and clean data from two marketing campaigns.
2. Merge datasets and handle missing values.
3. Perform exploratory data analysis (EDA) and visualize key metrics.
4. Compare the performance of the Control and Test campaigns based on various metrics.

## Features

- Data Cleaning and Preparation
- Visualization of Key Metrics (Impressions, Clicks, Searches, etc.)
- Comparative Analysis of Campaign Performance
- Insights on Conversion Rates and Marketing Effectiveness

## Prerequisites

To run this Jupyter Notebook, you need the following Python packages:

- `pandas`
- `datetime`
- `plotly`
- `warnings`

You can install the required packages using the following command:

   ```bash
   pip install pandas plotly
   ```

## Dataset
The project requires two CSV files:

1. `control_group.csv` - Contains data for the Control Campaign.
2. `test_group.csv` - Contains data for the Test Campaign.
   
Ensure these files are in the same directory as the Jupyter Notebook.

## Running the Notebook
1. Clone the repository or download the Jupyter Notebook file.

   ```bash
   git clone https://github.com/mshaadk/AB-Testing-Marketing-Campaigns.git
   cd AB-Testing-Marketing-Campaigns
   ```

2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open the notebook file `AB Testing.ipynb`.

4. Execute the cells to perform the analysis.

## Analysis
### Data Preparation
- **Column Renaming**: Standardized column names across both datasets.
- **Handling Missing Values**: Filled missing values in the Control Campaign dataset with the mean of each column.
- **Merging Datasets**: Combined Control and Test campaign data for comparison.
  
### A/B Testing Analysis
- **Impressions vs. Amount Spent**: Scatter plot showing the relationship between impressions and spending.
- **Searches and Clicks**: Pie charts comparing searches performed and website clicks for both campaigns.
- **Content Viewed and Cart Additions**: Pie charts analyzing content viewed and products added to the cart.
- **Purchase Comparison**: Pie chart comparing total purchases from both campaigns.
  
### Conversion Metrics
- **Clicks vs. Content Viewed**: Scatter plot analyzing website clicks relative to content viewed.
- **Content Viewed vs. Products Added**: Scatter plot evaluating the relationship between content viewed and products added to the cart.
- **Products Added vs. Purchases**: Scatter plot showing the relationship between products added to the cart and total purchases.
  
## Conclusion
- **Control Campaign**: Demonstrated higher overall engagement and conversion, leading to more products added to the cart and higher sales.
- **Test Campaign**: Showed a higher conversion rate for products added to the cart, suggesting a more targeted approach.
  
Based on the analysis, the Control Campaign is more effective for broader audience engagement, while the Test Campaign may be used for targeted marketing strategies.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.

## Contact
For questions or feedback, please contact [Mohamed Shaad](https://www.linkedin.com/in/mohamedshaad/).
