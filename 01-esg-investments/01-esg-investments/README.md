# Project 1 – ESG Investment Dashboard

### Goal
Explore World Bank indicators related to renewable energy, fossil fuel use, and CO₂ emissions.  
Prepare a clean dataset for further modeling in dbt and visualization in Looker Studio.

### Data
- Source: World Bank Open Data (API)  
- Indicators:
  - EG.FEC.RNEW.ZS → Renewable energy consumption (% of total final energy)  
  - EG.USE.COMM.FO.ZS → Fossil fuel consumption (% of total)  
  - EN.ATM.CO2E.PC → CO₂ emissions (tons per capita)

### Folder structure
- `data/raw/` – raw files (if saved)  
- `data/processed/` – cleaned CSVs ready for analysis  
- `notebooks/` – Jupyter notebooks with EDA & analysis  
- `src/` – (future) Python scripts, ETL pipeline

### How to run
1. Clone the repo & create venv  
2. `pip install -r requirements.txt`  
3. Run `jupyter notebook`  
4. Open `notebooks/esg_investments_analysis.ipynb`