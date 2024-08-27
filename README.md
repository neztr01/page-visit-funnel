# Page Visits Funnel Project
## Overview
> This project is part of the Codecademy's Path. Data Science: Machine Learning / NLP Specialist. This project analyzes the user funnel of an e-commerce website to identify where users drop off in the purchasing process. By merging and analyzing data from different stages (visits, cart, checkout, and purchase), we can identify the conversion rates and the weakest points in the funnel. The analysis provides actionable insights to improve the user experience and potentially increase conversion rates.

## Dataset
> The project uses four CSV files representing different stages of the user journey on the website:

- `visits.csv`: Records of users visiting the site.
- `cart.csv`: Records of users adding items to their cart.
- `checkout.csv`: Records of users proceeding to checkout.
- `purchase.csv`: Records of users completing their purchase.

## Objectives
1. Data Inspection:
    - Load and inspect the datasets to understand the structure and content.

2. Merging Datasets:
    - Merge the datasets to create a comprehensive view of the user journey across the funnel.

3. Funnel Analysis:
    - Calculate the conversion rates at each stage of the funnel:
        - Visitors who add items to the cart.
        - Users who proceed to checkout after adding items to the cart.
        - Users who complete the purchase after reaching the checkout.
    - Identify the percentage of users who drop off at each stage.

4. Actionable Insights:
    - Analyze the data to provide recommendations on how to reduce drop-off rates and improve conversion.

## Key Metrics
- **Percentage of Users Not Adding to Cart**: Calculate the percentage of visitors who do not add items to their cart.
- **Percentage of Users Not Proceeding to Checkout**: Determine the percentage of users who add items to their cart but do not proceed to checkout.
- **Percentage of Users Not Completing Purchase**: Calculate the percentage of users who proceed to checkout but do not complete their purchase.

## Insights
- The analysis revealed that the highest drop-off occurred at the "adding to cart" stage, suggesting that improvements in UI/UX or offering incentives like discounts might encourage more users to add items to their cart.
- Additional recommendations include A/B testing different checkout designs to minimize drop-off at the checkout stage.

## Technologies Used
- **Pandas**: For data manipulation and analysis.
- **Python**: For scripting and performing the analysis.

## Next Steps
- **Visualization**: Add data visualizations to better represent the conversion rates and drop-off points.
- **Advanced Analysis**: Implement predictive models to forecast user behavior and potential improvements.
- **A/B Testing**: Design and simulate A/B tests based on the insights derived from the analysis.
  
## Conclusion
> This project demonstrates the application of data analysis techniques to understand user behavior in an e-commerce setting. By identifying where users are dropping off in the funnel, actionable strategies can be developed to improve the overall user experience and conversion rates.

## How to Run
1. Clone the repository.
2. Ensure you have the required libraries (pandas).
3. Place the CSV files (visits.csv, cart.csv, checkout.csv, purchase.csv) in the working directory.
4. Run the script to perform the analysis.
