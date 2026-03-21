# Healthcare Claims Cost Analysis

## Database Creation

## Business Problem
A healthcare insurance company struggles with rising claim costs. 

## Objective
Analyze healthcare data in claims to highlight key cost drivers and, based on data-driven evidence, provide recommendations to reduce overall healthcare spending while improving patient outcomes and satisfaction.

## Tools Used
- Python (Anaconda, Pandas, Jupyter, NumPy, and Matplotlib)
- SQL (PostgreSQL and Bash)
- CSV File
- Power BI

## Main Insights
- Top 20% of patients contribute heavily to healthcare costs
- ER visits are the highest cost per visit average
- Chronic conditions like heart disease and diabetes are the main contributors to increased total spending
- Certain providers cost disproportionately compared to others
- Healthcare spending is impacted by seasonal trends

## Business Impact 
These data-driven insights can enable healthcare organizations to reduce unnecessary costs, improve organizational efficiency, and improve patient outcomes, care, and satisfaction.

## Files Included
- Jupyter Notebook with fill analysis
- CSV outputs from analysis
- Visualizations (Graphs)
- Power BI File

  ## Sample Visualization of Database

  ![Cost by Condition](cost_by_chronic_condition_chart.png)

  ## Sample Visualization of Dashboard
  ![Dashboard Screenshot]([HealthcareClaimsCostAnalysisDashboard.pdf](https://github.com/CharlesB163/healthcare-claims-analysis/blob/Creating-Database/HealthcareClaimsCostAnalysisDashboard.pdf)

  ## Interactive Version

 [View Interactive Dashboard on Power BI](https://app.powerbi.com/groups/me/reports/77df9b9b-318d-4032-9d12-d1da1b69b162?ctid=cfa792cf-7768-4341-8857-81754c2afa1f&pbi_source=linkShare)

## How to Run the Project
1. Open the `.pbix` file in Power BI Desktop to view the dashboard interactively.  
2. Ensure that the included CSV files (`patients_clean.csv`, `providers_clean.csv`, `claims_clean.csv`) are in the same folder as the `.pbix` file.  
3. Optionally, Python scripts (`DataScript.ipynb`) can be run to generate or update the CSV files from raw simulated data.  
  
