ds_<candidate_name>/
├── notebook_1.ipynb # Main Google Colab notebook with analysis
├── csv_files/ # Stores all input and processed CSV files

├── outputs/ # Stores all charts, plots, and visual results
│ └── *.png / *.jpg
├── ds_report.pdf # Final summarized insights and findings
└── README.md # Project documentation


## 📌 Objective
The goal of this project is to explore the relationship between **trader performance** and **market sentiment** (Fear vs Greed). By combining sentiment data with historical trading records, we analyze how sentiment influences profitability, risk, and behavior.

## 📂 Datasets
1. **Bitcoin Market Sentiment Dataset**
   - Columns: `Date`, `Classification` (Fear / Greed)

2. **Hyperliquid Historical Trader Dataset**
   - Columns include: `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, etc.

## ⚙️ Setup
1. Open `notebook_1.ipynb` in **Google Colab**.  
2. Upload the datasets into the `csv_files/` directory or load them directly from source.  
3. Run the notebook cells step by step to generate processed CSVs and visualizations.  
4. Plots and charts will be saved inside the `outputs/` directory.  

## 📊 Analysis Performed
- Merged datasets on date to align trades with daily sentiment.  
- Calculated metrics:  
  - Total trades per sentiment  
  - Average profit/loss (PnL)  
  - Win rate by sentiment  
  - Largest profit & loss trades  
- Created multiple visualizations:  
  - Distribution of trades by sentiment  
  - Profitability vs sentiment  
  - Boxplots of profit distributions  
  - Correlation heatmap of trader metrics  

## 📑 Report
The final findings are summarized in **`ds_report.pdf`**, which explains the insights in human-readable form:
- Fear markets lead to deeper losses.  
- Greed markets encourage more activity and higher profits.  
- Sentiment strongly influences trader psychology and outcomes.  

## 🚀 How to Run
- Clone the repo or download the folder.  
- Open `notebook_1.ipynb` in Google Colab.  
- Run all cells to reproduce results.  
