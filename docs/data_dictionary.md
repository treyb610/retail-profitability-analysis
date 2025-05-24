# Data Dictionary

## Original Dataset: Sample Superstore.csv

| Column Name | Data Type | Description | Example |
|-------------|-----------|-------------|---------|
| Row ID | Integer | Unique identifier for each record | 1, 2, 3 |
| Order ID | String | Unique order identifier | CA-2016-152156 |
| Order Date | Date | Date when order was placed | 11/8/2016 |
| Ship Date | Date | Date when order was shipped | 11/11/2016 |
| Ship Mode | String | Shipping method | Standard Class, First Class |
| Customer ID | String | Unique customer identifier | CG-12520 |
| Customer Name | String | Customer full name | Claire Gute |
| Segment | String | Customer segment | Consumer, Corporate, Home Office |
| Country | String | Country name | United States |
| City | String | City name | Henderson |
| State | String | State name | Kentucky |
| Postal Code | Integer | ZIP/Postal code | 42420 |
| Region | String | Geographic region | South, West, East, Central |
| Product ID | String | Unique product identifier | FUR-BO-10001798 |
| Category | String | Product category | Furniture, Office Supplies, Technology |
| Sub-Category | String | Product sub-category | Bookcases, Storage, Phones |
| Product Name | String | Full product name | Bush Somerset Collection Bookcase |
| Sales | Float | Sale amount in USD | 261.96 |
| Quantity | Integer | Number of items ordered | 2 |
| Discount | Float | Discount percentage | 0.00 (0% to 80%) |
| Profit | Float | Profit amount in USD | 41.91 |

## Calculated Fields

| Field Name | Formula | Description |
|------------|---------|-------------|
| Profit Margin | Profit / Sales | Profitability percentage |
| Unit Price | Sales / Quantity | Price per individual item |
| Days to Ship | Ship Date - Order Date | Shipping duration |
