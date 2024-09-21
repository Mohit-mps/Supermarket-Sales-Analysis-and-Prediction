# Supermarket-Sales-Analysis-and-Prediction

<h2> Problem Statement:</h2>

The following dataset is obtained from Kaggle.
This project aims to analyze and predict sales patterns based on customer and transaction data from a supermarket dataset. The task is to identify key factors driving sales and generate insights for optimizing sales strategies and improving operational efficiency.

<h2> Data Overview/Variable Description:</h2>

- Order ID: Unique identifier for each order.
- Order Date: Date when the order was placed.
- Ship Date: Date when the order was shipped.
- Ship Mode: Shipping mode (e.g., Second Class, Standard Class).
- Customer ID: Unique identifier for each customer.
- Customer Name: Name of the customer.
- Segment: Customer segment (Consumer, Corporate, etc.).
- Country: Country of the transaction.
- City: City of the customer.
- State: State of the customer.
- Postal Code: Postal code of the customer.
- Region: Geographic region (e.g., West, South).
- Product ID: Unique identifier for the product.
- Category: Product category (e.g., Furniture, Office Supplies).
- Sub-Category: Sub-category of the product.
- Product Name: Name of the product.
- Sales: Sales amount for the product.

<h2> Data Cleaning, EDA, and Feature Engineering: </h2>

- Handling Missing Values: The dataset contains a small number of missing values in the Postal Code column (11 entries). These missing values were handled appropriately, either through imputation or removal.
- Data Type Conversion: The date columns (Order Date, Ship Date) were converted into proper datetime objects for further analysis.
- Exploratory Data Analysis (EDA): Visualized key relationships between product categories and sales, identifying top-selling products and customer segments.
- Explored trends over time, focusing on sales performance by region and shipping mode.
- Feature Engineering: Created new features from the date columns, such as month and year, to analyze sales trends over time.
- Grouped data by customer segments to investigate differences in purchasing behavior.

<h2> Modeling: </h2>

For predictive analysis, a Gradient Boosting model can be deployed to predict sales based on factors such as customer segment, region, product category, and shipping mode. This helps in:

- Predicting future sales for different product categories.
- Identifying key drivers behind high sales performance, helping optimize inventory and marketing strategies.
