# Consolidated-Financial-Statements-MWG-
This is an analysis and modeling based on MWG's publicly available financial reports for 2022, 2023, and 2024.
# MWG Financial Report Analysis

This repository provides a comprehensive analysis of MWG's financial statements using Python and Jupyter Notebook. The project includes data transformation, visualization, and financial health assessment models such as Piotroski F-score and Altman Z-score.

## Features

- **Data Transformation:** Converts raw financial data into a columnar format for easy analysis.
- **Visualization:** 
  - Line charts and bar charts for each financial metric by year.
  - Grouped bar charts for comparing multiple metrics.
  - Dashboards for a quick overview of key indicators.
- **Financial Health Models:**
  - **Piotroski F-score:** Evaluates the quality of financial health based on 9 criteria.
  - **Altman Z-score:** Predicts bankruptcy risk using key balance sheet and income statement ratios.
- **Automated Conclusions:** Generates summary assessments of MWG's financial health based on model results and key ratios.

## How to Use

1. **Prepare Data:**  
   Place your `Finance_MWG.csv` file in the project directory. The file should include columns such as `Metric`, `Unit`, and yearly data.

2. **Run the Notebook:**  
   Open `Untitled-1.ipynb` in Jupyter Notebook or VS Code and run all cells.

3. **View Results:**  
   - Processed data will be saved as `Finance_MWG_by_year.csv`.
   - Visualizations and dashboards will be displayed inline.
   - Financial health conclusions will be printed at the end of the notebook.

## Requirements

- Python 3.x
- pandas
- matplotlib

Install dependencies with:
```bash
pip install pandas matplotlib
```

## Models Explained

### Piotroski F-score
- Scores from 0 to 9 based on profitability, leverage, liquidity, and operating efficiency.
- **7–9:** Very good financial health.
- **5–6:** Average, monitor closely.
- **Below 5:** Financial risk present.

### Altman Z-score
- Predicts bankruptcy risk.
- **Z > 2.99:** Safe zone.
- **1.81 < Z < 2.99:** Warning zone.
- **Z < 1.81:** High risk of bankruptcy.

## Output

- **Charts:** For each metric and summary dashboards.
- **CSV:** Cleaned, columnar financial data.
- **Text Summary:** Automatic financial health assessment.

## License

This project is for educational and analytical purposes.

---

**Author:** [Your Name]  
**Contact:** [Your Email]
