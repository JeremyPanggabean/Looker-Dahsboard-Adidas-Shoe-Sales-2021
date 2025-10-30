# 👟 Adidas Shoe Sales Performance Looker Dashboard 2021  

### 📊 Project Overview  
This project presents a **business intelligence dashboard** analyzing Adidas shoe and apparel sales throughout **2021**.  
The dashboard provides insights into **total revenue, unit sales, operating profits, product performance, and sales distribution** across regions and retailers.  

The visuals were designed using **Google Looker Studio** with a clean corporate-style layout inspired by BI tools such as Tableau and Power BI.  

🔗 **Live Dashboard:** [View on Looker Studio](https://lookerstudio.google.com/reporting/65dd8820-2943-4a18-a3cf-0e08d2e1ac71)  

---

### 🧾 Dataset  
**Source:** Custom dataset prepared in Google Sheets (2021 Adidas sales sample).  
**File:** [`Data/Adidas Shoe Sales_2021.csv`](Data/Adidas%20Shoe%20Sales_2021.csv)  

| Column | Description |
|---------|-------------|
| `Invoice_Date` | Date of transaction |
| `Region` | Sales region (South, West, Midwest, etc.) |
| `State` | U.S. state where the sale occurred |
| `City` | City of the retailer |
| `Product` | Product category (e.g., Men Street Footwear, Women Apparel) |
| `Price_per_Unit` | Unit price of the product (USD) |
| `Unit_Sold` | Total units sold |
| `Total_Sales` | Total revenue generated (USD) |
| `Operating_Profit` | Operating profit from the sales (USD) |
| `Sales_Method` | Channel type: Online, In-store, or Outlet |

---

### 🎯 Objectives  
The dashboard aims to:  
- Track **total revenue**, **units sold**, and **average profit margin**.  
- Compare performance across **product categories** and **retailers**.  
- Understand **sales distribution by method** (Online, Outlet, In-store).  
- Analyze the **relationship between profit and unit sales**.  
- Visualize **geographical sales distribution** across U.S. cities.  

---

### 📈 Dashboard Pages  

#### **📍 Page 1 — Adidas Sales Performance Overview**  
![Adidas Sales Performance Overview](Images/Adidas%20Sales%20Performance_Page%201.jpg)

**Highlights:**  
- **Key Metrics:** Total Sales (USD), Units Sold, and Avg Operating Profit.  
- **Bar Chart:** Operating Profit by Product Category.  
- **Donut Chart:** Sales Method Distribution (Online, Outlet, In-store).  
- **Scatter Plot:** Relationship between Unit Sold and Operating Profit.  
- **Line Chart:** Total Units Sold by Retailer.  

💡 *This page serves as a financial and operational summary of Adidas’s 2021 sales performance.*

---

#### **🗺️ Page 2 — Adidas Sales Bubble Map Based on City**  
![Adidas Sales Bubble Map](Images/Adidas%20Sales%20Buble%20Map%20Based%20on%20City_Page%202.jpg)

**Description:**  
An interactive **geo bubble map** visualizing total sales per city and retailer.  
- The **bubble size** represents total sales value.  
- The **color** distinguishes between different retailers.  
- Concentrated bubbles in the Midwest and South regions indicate strong sales activity in those areas.  

---

### ⚙️ Tools & Technologies  
- **Google Sheets** → Data cleaning and preparation  
- **Google Looker Studio** → Dashboard creation and visualization  
- **Excel** → Data preprocessing  
- **Canva / Figma** → Visual design and layout polishing (logo & theme colors)

---

### 💡 Key Insights  
- *Men Street Footwear* and *Women Apparel* recorded the **highest operating profits**.  
- **Online sales** dominate with **46.4% of total transactions**, reflecting post-pandemic digital behavior.  
- *West Gear* led total unit sales among retailers.  
- Strong positive correlation observed between **Operating Profit** and **Units Sold**, highlighting operational efficiency.  
- The **Midwest region** achieved higher profitability compared to other regions.  

---

### 🧭 Project Structure  
