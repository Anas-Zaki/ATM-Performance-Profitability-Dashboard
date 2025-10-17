# 📊 ATM Performance & Profitability Dashboard

## 📝 Project Overview
The **ATM Performance & Profitability Dashboard** project provides a detailed analysis of ATM operations across multiple states. It examines transaction counts, revenue, operational costs, uptime, and profitability to generate actionable insights. The goal is to help business teams make data-driven decisions for optimizing ATM placement, reducing costs, and improving overall efficiency.  
This project uses **Power BI** for interactive dashboards and **Pandas, Matplotlib, and Seaborn** for cleaning, analysis, and visualizations.

---
## 🧾 Dataset

**Files Provided:**

- `data/Row_Data.xlsx`          – Original raw dataset  
- `data/cleaned_data.csv`   – Preprocessed dataset ready for analysis


## 🗂️ Key Dataset Columns & Descriptions
| Column Name                 | Description                                                            |
| --------------------------- | ---------------------------------------------------------------------- |
| Year / Month                | Time period of ATM data collection.                                    |
| ATM ID                      | Unique identifier for each ATM.
| Fin Txn                     | Number of financial transactions (cash withdrawals, deposits)          |
| Non Fin Txn                 | Number of non-financial transactions (balance inquiry, mini-statement) |
| CRA                         | Cost Recovery Amount or fees collected for recovery                    |
| Spare Rep. (SLM) (AssetOEM) | Cost of spare parts replaced under Asset OEM agreements                |
| Site Maint (Non Asset)      | Site maintenance costs not related to ATM assets                       |
| Spare Rep.(UPS)             | Cost of UPS (backup power) spare repairs                               |
| FLM                         | Field Level Maintenance costs                                          |
| ATM AMC                     | Annual Maintenance Contract costs for ATM machines                     |
| VSAT AMC                    | Maintenance costs for VSAT (satellite communication) services          |
| Revenue Performance         | Categorical indicator (High, Medium, Low) of revenue performance       |
| Up Time                     | Percentage of time the ATM was operational during the month            |

---
## 📁 Project Structure
```
ATM_Performance_Dashboard/
│── 📄 README.md                        # Project documentation
│── 📂 data/                            # Raw and cleaned datasets
│   │── 📄 Row_Data.xlsx                # Original dataset
│   │── 📄 cleaned_data.csv             # Cleaned dataset for analysis and dashboard
│── 📂 notebooks/                       # Analysis and visualization files
│   │── 📄 Cleaning_Process.ipynb       # Data cleaning steps
│   │── 📄 Visualization.ipynb          # EDA and visualizations
│   │── 📄 ATM_Transaction.pbix         # Power BI dashboard
```



## 📸 Dashboard Snapshots

### 1️⃣ Dashboard Overview  
Shows key metrics such as revenue, uptime, transactions, and cost distribution across states.  

<img width="1031" height="579" alt="image" src="https://github.com/user-attachments/assets/5488e528-16d9-4acb-9427-c536fbdd9bc8" />

### 2️⃣ Detailed Insights  
Provides state-level performance detailed cost breakdown.  

<img width="1030" height="582" alt="image" src="https://github.com/user-attachments/assets/084a92ff-4f87-4495-8202-935f89acac27" />


## 📸 Key Visualizations

### 💰 Total Cost vs Gross Profit by State
<img width="1101" height="573" alt="image" src="https://github.com/user-attachments/assets/5655a103-f4d7-486a-98ed-4e3ae5293f99" />

| |
|---|
| **Assam** leads with a **gross profit of ₹161M** against a **total cost of ₹123M**, showing strong profitability.<br> **Punjab** (**₹72M profit, ₹76M cost**) and **Jammu & Kashmir** (**₹25.7M profit, ₹37M cost**) have tighter margins.<br> **Manipur (₹21.9M, ₹15.9M)**, **Nagaland (₹15.7M, ₹10M)**, and **Tripura (₹15.3M, ₹10.4M)** are moderately profitable.<br> **Meghalaya (₹11.6M, ₹6.6M)**, **Mizoram (₹9.9M, ₹4M)**, **Arunachal Pradesh (₹5.8M, ₹7.5M)**, **Ladakh (₹1.7M, ₹3.3M)**, and **Sikkim (₹1.56M, ₹2.3M)** show lower margins, highlighting opportunities for **cost optimization and strategic focus**. |



### 💳 Financial vs Non-Financial Transactions
<img width="1212" height="626" alt="image" src="https://github.com/user-attachments/assets/a4f2fe8a-8354-42e6-b43f-0f16b7a28753" />

| |
|---|
|**Assam** leads with **21.36M financial** and **5.28M non-financial transactions**, followed by **Punjab (12.85M, 2.17M)**.  
Mid-level states like **Jammu & Kashmir, Manipur, Nagaland, and Tripura** show moderate activity, while smaller states such as **Meghalaya, Mizoram, Ladakh, and Sikkim** have low transactions.  
Financial transactions dominate, highlighting cash usage as the primary ATM service and guiding **ATM placement and cash planning**. |

### ⏱️ ATM Uptime Analysis
<img width="1105" height="581" alt="image" src="https://github.com/user-attachments/assets/bf152720-2b13-457b-8c43-c0c8a12a6baa" />


| |
|---|
|**Tripura** tops with **94% uptime**, followed by **Meghalaya, Assam, Mizoram, and Punjab** at **93%**, showing highly reliable ATM operations.  
**Ladakh and Jammu & Kashmir** are at **91%**, while **Manipur, Nagaland, Arunachal Pradesh, and Sikkim** range **80–90%**.  
Lower uptime states may see **reduced transactions and revenue**, emphasizing **targeted maintenance**. |


### 💰 Proportion of ATM Cost Components
<img width="813" height="614" alt="image" src="https://github.com/user-attachments/assets/456cd68f-378d-4370-9f6f-31a203843133" />

| |
|---|
|Costs are mainly from **ATM AMC (49.7%)** and **UPS spare repairs (26.1%)**, with moderate contributions from **VSAT AMC (9.9%)** and **site maintenance (9.4%)**, and minimal **UPS AMC (5%)**.  
Focus on **reducing ATM AMC and spare repair costs** to optimize expenses without affecting service quality. |



## 🛠️ Tech Stack & Tools
- **Power BI** – Interactive dashboard visualization  
- **Pandas** – Data cleaning and preprocessing  
- **Matplotlib & Seaborn** – Visualization of trends and insights  

---
## 📌 Key Features
✔️ End-to-end data cleaning using **Pandas**.  
✔️ Interactive **Power BI** dashboard with filters, slicers, and dynamic visuals.  
✔️ Actionable business insights including top-performing states, cost optimization, and transaction trends.  
✔️ Detailed analysis of ATM operations: uptime, transaction types, revenue, and costs.  
✔️ Visual storytelling to support strategic decisions and performance monitoring.

---

## 🔧 Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Anas-Zaki/ATM-Performance-Profitability-Dashboard.git
   cd ATM-Performance-Profitability-Dashboard
   ```
2. **Install required libraries:**
- `Power-Bi`
- `pandas`
- `matplotlib`
- `seaborn`

You can install them using pip:
 ```bash
  pip install pandas matplotlib seaborn
   ```
For Power-Bi you can visit this website 
```bash
https://www.microsoft.com/en-us/download/details.aspx?id=58494
```
3. Open the Power BI file RetailPulse_Dashboard.pbix.
4. Explore the Jupyter Notebook notebooks and insights.

## 🔮 Future Improvements
- Add forecasting & predictive analytics using Power BI AI features.
- Connect to a real-time ATM data source for live updates.
- Implement automated reporting to generate PDFs or emails for management.


## 📜 License
This project is open-source and available for modification and distribution.

---

📩 **Contributions & Feedback**         
Feel free to fork the repository, submit issues, or suggest improvements!


Happy Coding! 🚀


