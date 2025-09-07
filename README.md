# 📊 Assessment – ETRM Data Analysis with Pandas & Visualization  

## 🎯 Objective  
To practice **data ingestion, transformation, and visualization** using **Pandas** and Python plotting libraries (**Matplotlib / Seaborn / Plotly**).  

This project demonstrates how to handle multi-format synthetic **ETRM trade data**, clean & transform it, perform exploratory data analysis (EDA), and generate insights through visualizations.  

---

## 📂 Dataset Description  
You are provided with synthetic trade data in **six formats**:  
- CSV (`etrm_trades.csv`)  
- JSON (`etrm_trades.json`)  
- Excel (`etrm_trades.xlsx`)  
- Text (pipe-delimited) (`etrm_trades.txt`)  
- HTML (`etrm_trades.html`)  
- XML (`etrm_trades.xml`)  

Each file contains **100 trades** with the following fields:  
- `TradeID`  
- `Trader`  
- `Commodity`  
- `Volume`  
- `Price`  
- `Currency`  
- `DeliveryStart`  
- `DeliveryEnd`  
- `Periodicity`  

---

## 🛠️ Steps Performed  

### 1️⃣ Data Ingestion  
- Loaded all six file formats into Pandas DataFrames.  
- Standardized **column names and data types** across files.  

### 2️⃣ Data Cleaning & Transformation  
- Converted `DeliveryStart` and `DeliveryEnd` columns to **datetime format**.  
- Added **Notional Value** column = `Volume × Price`.  
- Ensured **data consistency** across all sources.  

### 3️⃣ Exploratory Data Analysis (EDA)  
Performed key analyses, including:  
- 📌 **Top 5 traders** by total trade volume  
- 📌 **Average price** per commodity  
- 📌 **Distribution of trades** by currency  
- 📌 **Breakdown of trade periodicity** (Daily, Weekly, Monthly, etc.)  
- 📌 **Trend analysis** of average prices by delivery start date  

### 4️⃣ Data Visualization  
Generated at least **5 plots** for insights:  
- 📊 **Bar Chart** → Volume by trader  
- 🥧 **Pie Chart** → Trades by currency  
- 📈 **Line Chart** → Average price trend by delivery start date  
- 📉 **Histogram** → Distribution of notional values  
- 🔥 **Heatmap** → Commodity vs. Trader trade counts  

---

## 📒 Deliverables  

- **Code**:  
  - `ETRM.ipynb` → Jupyter Notebook with data ingestion, transformation, and visualization.  
  - `ETRM_Assessment.py` (optional) → Python script version for automation.  

- **Summary Report**:  
  - `Insights_Summary.md` (or Word/PDF) → Key findings from the data analysis.  

- **Datasets**:  
  - Provided in multiple formats inside the `datasets/` folder.  

---

## 🚀 How to Run  

### 1. Clone the Repository  
```bash
git clone https://github.com/animesharyan07/Assesment2
cd Assesment2


### 2. Install Dependencies
```bash
pip install -r requirement.txt
