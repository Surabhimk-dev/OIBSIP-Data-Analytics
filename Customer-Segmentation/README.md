# Customer Segmentation Analysis

## About the Project

In this project, I analyzed customer transaction data to understand different types of customers based on their purchasing behavior.

I used **RFM analysis** and **K-Means clustering** to divide customers into different groups.

RFM stands for:

- **Recency** – How recently a customer made a purchase
- **Frequency** – How often a customer makes a purchase
- **Monetary** – How much a customer spends

## Objective

The main objectives of this project were:

- Understand customer purchasing behavior
- Clean and prepare the dataset
- Calculate RFM values
- Group similar customers using K-Means
- Understand the different customer segments
- Suggest suitable marketing strategies

## Dataset

I used the **Online Retail Dataset**.

The dataset contains information about customer transactions, including invoice number, product, quantity, price, date, customer ID, and country.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Data Cleaning

Before starting the analysis, I cleaned the dataset by:

- Checking for missing values
- Removing records without Customer ID
- Removing duplicate records
- Removing invalid quantities
- Removing invalid prices
- Converting the invoice date into the correct format

I also created a new `TotalAmount` column using:

```text
TotalAmount = Quantity × UnitPrice
```

## RFM Analysis

I calculated three values for each customer:

**Recency:** Shows how recently the customer purchased.

**Frequency:** Shows how often the customer purchased.

**Monetary:** Shows how much the customer spent.

These values were used to understand customer behavior.

## Customer Segmentation

The RFM values were standardized using `StandardScaler`.

I then used the **Elbow Method** to find a suitable number of clusters.

Based on the Elbow Method, I selected **4 clusters**.

K-Means clustering was then used to divide the customers into four groups.

## Visualizations

The project includes visualizations for:

- Recency distribution
- Purchase frequency
- Customer spending
- Elbow Method
- Number of customers in each cluster
- Frequency vs Monetary
- Recency vs Monetary

## Business Insights

The clustering helped identify customers with different purchasing behaviors.

Some customers purchase frequently and spend more, while others purchase less often or have not purchased recently.

This information can help a business understand its customers better and create more targeted marketing campaigns.

## Marketing Recommendations

For high-value customers, the business can provide loyalty rewards, exclusive offers, and personalized recommendations.

For loyal customers, the business can provide repeat-purchase offers and loyalty benefits.

For customers who have not purchased recently, the business can use re-engagement emails and special discounts.

For low-value customers, the business can use simple promotional offers and product recommendations.

## Conclusion

This project helped me understand how customer transaction data can be used to identify different customer groups.

Using RFM analysis and K-Means clustering, I divided customers into four segments and studied their purchasing behavior.

The results can help businesses create better marketing strategies and improve customer engagement and retention.

## Author

**Surabhi M K**