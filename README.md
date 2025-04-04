# E-Commerce Data Analysis

This project analyzes an e-commerce dataset to extract valuable insights, identify trends, and make recommendations that can improve business performance. The analysis includes customer behavior, product sales, seasonal trends, and payment preferences. The goal is to help the company optimize its marketing, sales strategy, and improve customer experience.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Setup Instructions](#setup-instructions)
4. [Usage](#usage)
5. [Key Findings](#key-findings)
6. [Recommendations](#recommendations)

## Project Overview

This project uses Python and Jupyter Notebook to perform exploratory data analysis (EDA) on an e-commerce dataset. The goal is to provide actionable insights that can help improve sales and customer engagement. The analysis covers multiple aspects such as:

- Revenue trends by category and season
- Payment preferences and their impact on sales
- Customer satisfaction by gender and product category
- Correlations between key variables such as price, quantity, and revenue

## Dataset

The dataset contains transactional data from an online retail platform. The columns include:

- **customer_id**: ID of the customer
- **order_date**: Date of the transaction
- **product_id**: ID of the product
- **category_id**: Category ID of the product
- **category_name**: Name of the product category
- **product_name**: Name of the product
- **quantity**: Quantity of products purchased
- **price**: Price per unit of the product
- **payment_method**: Payment method used (e.g., Credit Card, Bank Transfer)
- **city**: City of the customer
- **review_score**: Rating given by the customer (1 to 5)
- **gender**: Gender of the customer
- **age**: Age of the customer

You can download the dataset from [here](https://www.kaggle.com/datasets/ertugrulesol/online-retail-data/data).

## Setup Instructions

```bash
1. Clone this repository to your local machine:
   git clone https://github.com/yourusername/e-commerce-data-analysis.git

2. Navigate to the project folder:
   cd e-commerce-data-analysis

3. Create a virtual environment (optional but recommended):
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

4. Install the required libraries:
   pip install -r requirements.txt

   *Note: If you don't have a `requirements.txt` file, you can manually install dependencies like pandas, matplotlib, and numpy:*
   pip install pandas matplotlib numpy
```

## Usage

```bash
1. Open the Jupyter Notebook:
   jupyter notebook

2. Open the `ecommerce_analysis.ipynb` file to view the analysis.

3. Run each cell in the notebook to see the results, visualizations, and insights.
```

## Key Findings

```markdown
- **Revenue Drivers**:
  - Price and quantity show a strong correlation with revenue.
  - Increasing price and quantity can significantly boost revenue.
  - Product categories such as Electronics and Sports & Outdoors generate the most revenue.
  - The younger generation is less represented in the customer base; strategies to attract them could increase sales.

- **Seasonal Trends**:
  - Electronics have high revenue in the Summer, while Fashion and Home & Living see lower sales in Spring.
  - Fashion products have low sales overall and should be promoted more during the off-seasons.

- **Payment Preferences**:
  - A large portion of customers prefer cash on delivery, indicating possible trust issues with online payment methods.
  - Bank transfers are the second most popular payment method, and credit card usage is less common.

- **Customer Satisfaction**:
  - Overall, customer satisfaction is relatively consistent across genders, with minor differences in product category preferences.
```

## Key Takeaways from the Scatter Plot (Revenue vs. Age)

```markdown
- **No Strong Correlation**:
  - There is no significant linear relationship between age and revenue.
  - Age alone is not a reliable predictor of spending behavior.

- **High Variability**:
  - Both younger and older individuals exhibit a wide range of revenue values.
  - High revenue values are present across various age groups, indicating that spending is not consistently higher for any specific age group.

- **No Clear Trend**:
  - There is no consistent pattern showing that younger individuals spend more than older individuals or vice versa.
  - The data points are scattered without forming a discernible trend line.

### Summary:
- **Age is Not a Strong Predictor of Spending**: The scatter plot does not indicate that age is a primary factor in determining revenue.
- **Variable Spending Across Ages**: Revenue varies significantly within all age groups, suggesting that other factors (e.g., income, lifestyle, preferences) play a more significant role in spending behavior.
```

## Recommendations

```markdown
1. **Improve Trust in Credit Card Payments**:
   - There is a noticeable preference for cash on delivery and bank transfers. It’s essential to understand why customers avoid credit card payments. Feedback surveys can help improve security measures or clarify trust-related concerns.

2. **Boost Fashion and Home & Living Sales**:
   - Both categories see lower sales, particularly in Spring. Campaigns targeting trends and customer preferences could help push sales during off-peak seasons.

3. **Exceed Expectations in Gender-Specific Products**:
   - Although the gender satisfaction is balanced, there is room to exceed expectations by offering more tailored experiences and products for each gender.

4. **Attract Younger Generations**:
   - Most of the customer base is older, which could be a missed opportunity. The company should explore ways to make the website more appealing to younger customers, such as optimizing navigation and making design improvements.
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The dataset used for this project was provided by [Ertuğrul EŞOL](https://www.kaggle.com/ertugrulesol).
```
