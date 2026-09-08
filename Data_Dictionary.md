# Data Dictionary – ApexPlanet Sales Dataset

This document describes the columns in the cleaned dataset.

| Column Name       | Data Type   | Description |
|-------------------|-------------|-------------|
| Order_ID          | String      | Unique identifier for each order (e.g., ORD100001). |
| Order_Date        | Date        | Date when the order was placed, standardized to YYYY-MM-DD format. |
| Customer_ID       | String      | Unique identifier for each customer (e.g., CUST5529). |
| Customer_Name     | String      | Customer’s name, standardized with proper casing. |
| Age               | Integer     | Age of the customer in years. |
| Gender            | String      | Gender of the customer (Male/Female). |
| City              | String      | City where the customer is located. |
| Product           | String      | Name of the product purchased. |
| Category          | String      | Product category (e.g., Grocery, Electronics, Fashion). |
| Quantity          | Integer     | Number of units purchased in the order. |
| Unit_Price        | Float       | Price per unit of the product. |
| Total_Sales       | Float       | Total sales value recorded in the dataset. |
| Total_Sales_Calc  | Float       | Recalculated sales value (Quantity × Unit_Price) for validation. |
| Sales_Match       | Boolean     | Flag indicating whether `Total_Sales` matches `Total_Sales_Calc`. |
| Order_Year        | Integer     | Extracted year from `Order_Date`. |
| Order_Month       | Integer     | Extracted month from `Order_Date`. |
| Order_Day         | Integer     | Extracted day from `Order_Date`. |
| Age_Group         | String    | Derived customer age group (Teen, Young Adult, Adult, Middle Age, Senior). |
| Customer_Age      | Integer     | Derived from Date of Birth (if available). |
