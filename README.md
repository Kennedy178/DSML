# DSML

# House Price Prediction

## Overview
this project involves a real estate company that focuses on optimizing listing prices for houses based on their characteristics. This project involves predicting house sale prices using historical data.

## Benefits
The project on predicting house prices using data analysis and machine learning has several potential beneficiaries:

### 1. **Home Buyers**
   - **Informed Decision-Making:** Buyers can gain insights into property values based on various features (e.g., number of bedrooms, location), helping them make informed purchasing decisions.
   - **Price Transparency:** By understanding average prices and variances for specific types of homes, buyers can better gauge whether a property is fairly priced.

### 2. **Real Estate Agents**
   - **Improved Pricing Strategies:** Agents can leverage the insights from the models to set competitive prices for listings, enhancing their ability to close sales.
   - **Targeted Marketing:** Understanding what drives prices can help agents tailor their marketing strategies to attract potential buyers based on specific property features.

### 3. **Investors**
   - **Investment Opportunities:** Investors can identify undervalued properties or neighborhoods with high growth potential based on predicted price trends.
   - **Risk Assessment:** By analyzing price variances, investors can better assess the risks associated with particular investments.

### 4. **Real Estate Developers**
   - **Market Analysis:** Developers can use insights to determine where to build new properties based on predicted demand and pricing trends in various areas.
   - **Product Development:** Understanding buyer preferences can guide the design and features of new developments to align with market demand.

### 5. **Policy Makers and Urban Planners**
   - **Urban Development Planning:** Insights into housing prices can inform city planning and zoning decisions, ensuring balanced development that meets community needs.
   - **Affordable Housing Initiatives:** By analyzing price trends, policymakers can better identify areas where affordable housing initiatives may be necessary.

### 6. **Financial Institutions**
   - **Mortgage Assessments:** Banks and lenders can use price predictions to assess risk more accurately when offering mortgages to homebuyers.
   - **Investment Strategies:** Financial institutions can develop investment products based on the predicted trends in real estate markets.

### Conclusion
The project not only helps individuals navigate the real estate market more effectively but also provides valuable data-driven insights that can improve business strategies, inform policy, and support community development efforts.

## Features
- Data cleaning and preprocessing
- Predictive modeling using Linear Regression and Random Forest Regressor
- Data analysis to understand the impact of various features on house prices

## Data
The dataset consists of historical house sales with the following features:
- `house_id`: Unique identifier for houses
- `city`: The city where the house is located
- `sale_price`: The sale price of the house in whole dollars
- `sale_date`: The date of the last sale of the house
- `months_listed`: Number of months the house was listed on the market
- `bedrooms`: Number of bedrooms in the house
- `house_type`: Type of house 
- `area`: Area of the house in square meters

## Installation
1. Clone the repository or download the files.
2. Navigate to the project directory.
3. Install the required packages using:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Ensure you have the necessary datasets (`house_sales.csv`, `train.csv`, `validation.csv`).
2. Run the Python script to clean data, fit models, and make predictions.

## License
This project is licensed under the MIT License.

## Acknowledgements
- Data sourced from [various online sources].
