 # 🛒 ShopNova E-Commerce Analytics Dashboard (Power BI)

![Dashboard](dashboard.png)

## 📌 Project Overview
An interactive Power BI dashboard built for ShopNova, an e-commerce business. It tracks sales, orders, payments, channels, cancellations and returns, helping the business see what drives revenue and where it loses sales.

## 🎯 Business Objective
- Track overall sales performance with key KPIs
- Identify top categories, products, payment methods and channels
- Monitor cancellations and returns to find operational gaps

## 🗂️ Data Model
- **Fact table:** Orders (7,562 orders)
- **Dimension tables:** Customers, Products, Calendar
- **Returns** linked to Orders on Order ID
- Star-schema relationships built in Power BI

## 🛠️ Tools & Skills Used
- **Power BI Desktop**: dashboard design and interactive visuals
- **DAX**: KPI measures (Revenue, AOV, GMV, Cancellation Rate %, Return Rate %)
- **Power Query**: data cleaning and transformation
- **Data Modelling**: relationships and calendar table

## 📊 Dashboard Features
- **6 KPI cards:** Total Revenue, Total Orders, Average Order Value, GMV, Cancellation Rate %, Return Rate %
- **6 visuals:** Monthly Sales Trend, Revenue by Category, Revenue by Payment Method, Orders by Order Status, Top 5 Products by Revenue, Orders by Channel
- **5 slicers:** Month, Category, Order Channel, Order Status, Payment Method

## 🔑 KPI Definitions
| KPI | Definition |
|---|---|
| Average Order Value | Delivered Final Amount / Delivered orders |
| Return Rate % | Returns / Delivered orders × 100 |
| Cancellation Rate % | Cancelled orders / Total orders × 100 |

## 💡 Key Insights
1. **Overall performance:** ShopNova generated **₹140.37M revenue** from **7,562 orders**, with an AOV of **₹18.56K** and GMV of **₹162M**. About 6.1K orders were delivered.
2. **Category concentration:** **Electronics contributes 77.07% of revenue (₹108.19M)**, so the business depends heavily on one category.
3. **Top products:** The top 5 products are all electronics: Apple iPhone (₹10.9M), Sony Alpha (₹10.7M), Dell Inspiron (₹9.3M), HP Pavilion (₹7.9M) and Asus Vivobook (₹7.3M).
4. **Sales trend:** Monthly revenue peaked early at about ₹29M and then declined steadily, which points to falling sales momentum.
5. **Payments:** **UPI leads with ₹46M**, followed by Credit Card (₹24M) and Cash on Delivery (₹23M). Net Banking is the lowest (₹8M).
6. **Channels:** The **Mobile App drives 50.82% of orders**, followed by Website (36.74%) and Social Commerce (12.44%).
7. **Cancellations and returns:** Both are about **8%**, with roughly 0.6K cancelled and 0.6K returned orders.

## 🎯 Recommendations
- Diversify beyond Electronics by promoting Fashion, Home and Beauty
- Investigate the sales decline and run targeted campaigns in weaker months
- Invest further in the Mobile App and grow Social Commerce
- Offer prepaid and UPI incentives to reduce Cash on Delivery risk
- Reduce cancellations and returns with better product information and stock accuracy

## 📁 Repository Contents
- `E-Commerce Analytics Dashboard PowerBI.pbix`: Power BI dashboard file
- `dashboard.png`: dashboard preview
- `README.md`: project documentation
- 
## 👤 Author
**Rohit Kumar Chauhan**, Data Analyst
[LinkedIn](https://www.linkedin.com/in/rohit-chauhan-8a457916a/) | [GitHub](https://github.com/Rohitchauhan0137)

