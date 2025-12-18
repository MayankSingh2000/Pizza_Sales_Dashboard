🍕 **Pizza Sales Analysis Dashboard (Excel + MS SQL Server)**

## 📌 Project Overview
This project focuses on analyzing pizza sales data to uncover meaningful business insights related to revenue, order patterns, customer behavior, and product performance.

The raw **Excel dataset** was first imported into **Microsoft SQL Server**, where **SQL queries were written for data validation, cleaning, and consistency checks**. After validation, the cleaned tables were **connected back to Excel using SQL Server connections**, and an **interactive dashboard** was built entirely in **Microsoft Excel**.

---

## 🛠 Tools & Technologies Used
- **Microsoft SQL Server & SQL Server Management Studio** – Data import, validation, and transformation using SQL queries  
- **Microsoft Excel** – Dashboard creation, KPIs, charts, and slicers  
- **SQL** – Data quality checks, aggregations, and validation  

---

## 📊 Dataset Information

- **Dataset Name:** Pizza Sales Dataset  
- **Data Source:** Publicly available sample dataset (commonly used for SQL & data analysis practice)  
- **Data Format:** Excel (.xlsx)  
- **Total Records:** ~48,000+ order-level records  
- **Time Period Covered:** One calendar year (monthly data available)  
- **Granularity:** Individual pizza order details  

---

### 📁 Tables / Columns Description

#### Orders & Time Details
- **order_id:** Unique identifier for each customer order  
- **order_date:** Date on which the order was placed  
- **order_time:** Time at which the order was placed  

#### Product Information
- **pizza_id:** Unique identifier for each pizza item  
- **pizza_name:** Name of the pizza  
- **pizza_category:** Category of pizza (Classic, Supreme, Veggie, Chicken)  
- **pizza_size:** Size of pizza (S, M, L, XL, XXL)  

#### Sales & Quantity Metrics
- **quantity:** Number of pizzas ordered per line item  
- **unit_price:** Price per pizza  
- **total_price:** Total price for the order line (quantity × unit_price)  

---

### 🔍 Data Preparation & Validation
- Dataset was first imported into **Microsoft SQL Server** for:
  - Duplicate checks  
  - Null value validation  
  - Price and quantity consistency checks  
  - Revenue calculation validation  

- Cleaned and validated tables were then connected to **Microsoft Excel** using a **SQL Server database connection** to build the dashboard.

---

### ⚠️ Notes
- This dataset is **synthetic / sample data** and is intended for **educational and portfolio purposes only**.  
- It does not represent real customer or business transactions.

---

## 📊 Key Performance Metrics
- **Total Revenue:** $817,860  
- **Total Orders:** 21,350  
- **Total Pizzas Sold:** 49,574  
- **Average Order Value:** $38.31  
- **Average Pizzas per Order:** 2.32  

---

## 📅 Order Trends & Time Analysis

### Orders by Day
- **Friday** records the highest number of orders, followed by **Saturday**.  
- **Sunday** has the lowest order volume.  
- Orders steadily increase from **Monday to Friday**, indicating strong weekday-to-weekend demand.

### Orders by Hour
- Peak ordering hours occur at **12 PM (lunch)** and **5–8 PM (dinner)**.  
- Maximum orders are observed around **12 PM**.  
- Orders decline significantly after **9 PM**.

### Busiest Periods
- **Friday and Saturday evenings** are the busiest business periods.  
- Clear dual peaks indicate strong **lunch and dinner demand cycles**.

---

## 🍕 Sales Analysis

### Sales by Pizza Category
- **Classic pizzas** contribute the highest share of total sales.  
- Supreme, Veggie, and Chicken categories show relatively balanced contributions.

### Sales by Pizza Size
- **Large-sized pizzas** generate the maximum sales.  
- **Medium and Regular sizes** follow next.  
- **XXL size** contributes minimally to overall sales.

### Total Pizzas Sold by Category
- **Classic** category leads in total pizzas sold.  
- **Supreme** and **Veggie** categories follow closely.  
- **Chicken pizzas** contribute the least in volume.

---

## 🏆 Product Performance

### Top 5 Best-Selling Pizzas (by Quantity Sold)
1. Classic Deluxe Pizza  
2. Barbecue Chicken Pizza  
3. Hawaiian Pizza  
4. Pepperoni Pizza  
5. Thai Chicken Pizza  

➡️ These pizzas are the **primary revenue and volume drivers**.

### Bottom 5 Worst-Selling Pizzas (by Quantity Sold)
- The Brie Carre Pizza (lowest performer)  
- Mediterranean Pizza  
- Calabrese Pizza  
- Spinach Supreme Pizza  
- Soppressata Pizza  

➡️ These items contribute the **least to both revenue and orders**.

---

## 🖼 Dashboard Preview
![image alt](https://github.com/MayankSingh2000/Pizza_Sales_Dashboard/blob/main/Docs/pizza_dashboard.png?raw=true)


---

## 📈 Business Insights & Takeaways
- Focus promotions on **Classic category and Large-sized pizzas**.  
- Ensure adequate staffing and inventory during **lunch and dinner peak hours**.  
- **Weekends**, especially Friday and Saturday evenings, offer the highest revenue potential.  
- Low-performing pizzas may require **menu optimization or promotional strategies**.

---

## 📂 Data Workflow
1. Excel data imported into **Microsoft SQL Server**  
2. Data validation and quality checks performed using **SQL queries**  
3. Cleaned tables connected to **Excel via SQL Server connection**  
4. Interactive dashboard developed in **Excel** using charts, KPIs, and slicers  

---

## 👤 Author
**Mayank Singh** 
-- Aspiring Data Analyst
-- Skilled in SQL, Power BI and Excel
-- Actively seeking entry-level Data Analyst opportunities



