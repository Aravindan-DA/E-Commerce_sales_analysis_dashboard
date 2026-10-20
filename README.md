🛒 E-Commerce Sales Data Analytics DashboardAn interactive Data Analytics Dashboard built to visualize performance metrics, sales trends, platform efficiency, shipping dynamics, and profitability across global markets.

📌 Project OverviewThis project processes raw transactional data to provide executive-level visibility into e-commerce operations. By leveraging DAX measures and dynamic visuals, the dashboard helps stakeholders understand revenue drivers, optimize fulfillment logistics, and identify high-value customer locations.

🧮 DAX Measures UsedHere are the core DAX formulas implemented to build dynamic calculations and KPIs across the dashboard:

Code snippet// 

1. Total Orders
Total Orders = COUNTROWS('Sales_Data')

// 2. Total Sales / Revenue
Total Revenue = SUMX('Sales_Data', 'Sales_Data'[Quantity] * 'Sales_Data'[Item_Price])

// 3. Units Sold
Units Sold = SUM('Sales_Data'[Quantity])

// 4. Total Cost
Total Cost = SUM('Sales_Data'[Product_Cost])

// 5. Total Gross Profit
Total Gross Profit = [Total Revenue] - [Total Cost]

// 6. Profit Margin %
Profit Margin % = DIVIDE([Total Gross Profit], [Total Revenue], 0)


📊 Key Business StatisticsTotal Orders: 1,000 Orders   Total Sales Revenue: $1.79M   Units Sold: 6,490 Units   Total Gross Profit: $588.35K   Overall Profit Margin: 32.84%  

📈 Dashboard Highlights & Insights

1. Sales & Cost by Shipping ModeExpress ($468.92K) and Economy ($468.17K) generate the highest sales revenue.   Express Shipping incurs the highest cost ($315.52K) relative to sales, making it a key area for cost optimization.

2. Sales by CategoryElectronics dominates sales revenue, generating $1,047K (over 58% of total sales).   Books ($52K) and Beauty ($106K) are underperforming categories that need promotional support.

3. Platform PerformanceShopify is the leading sales channel, bringing in $627K in Revenue and $205K in Gross Profit.   eBay ($584K Revenue / $197K Profit) and Amazon ($580K Revenue / $186K Profit) follow closely as consistent revenue channels.

4. Top Products AnalysisHigh-value tech goods lead the revenue contribution:Headphones: $254.29K   Laptop: $235.20K   Smartphone: $201.07K   Tablet: $184.33K   Smartwatch: $171.83K  

5. Geographic PerformanceJapan ranks highest in overall performance with $222,578.69 in Revenue and $72,973.92 in Profit.   France ($204.65K Revenue / $70.04K Profit) and India ($198.06K Revenue / $68.07K Profit) follow as high-yield international markets.  

💡 Strategic Business Actions

📉 Revenue Recovery: Address the monthly revenue slide (from peak $174.09K to $98.87K) by launching targeted re-engagement campaigns and seasonal discounts.   

📦 Logistics Negotiation: Renegotiate carrier contracts for Express Shipping to reduce fulfillment costs ($315.52K) and protect profit margins.   

🚀 Inventory Focus: Prioritize stock fulfillment for the Top 5 Electronics Products (Headphones, Laptops, Smartphones) to prevent stockouts.   

🌐 Regional Expansion: Allocate higher marketing budgets toward top-performing countries (Japan, France, and India) to maximize return on ad spend (ROAS).
