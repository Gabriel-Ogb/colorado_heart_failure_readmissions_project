CMS 30-Day Heart Failure Readmission – Colorado (2020 – 2023)
Colorado Hospital Performance Evaluation Using Python & Tableau

Executive Summary
This project analyzes 30-day heart failure readmission performance across Colorado hospitals (2020–2023) using publicly available CMS Hospital Compare data. The goal was to assess hospital performance relative to expected benchmarks, identify variation across facilities, and highlight opportunities for quality improvement.

Python was used for data preparation and metric engineering, while Tableau was used to build an interactive dashboard exploring excess readmission ratios, discharge volume, and CMS reporting eligibility. Hospitals were categorized by performance relative to the State benchmark to support comparative analysis.

Key findings reveal meaningful variation in readmission performance, limited interpretability for hospitals below CMS reporting thresholds, and no consistent relationship between discharge volume and performance. The final dashboard enables dynamic exploration through interactive filtering and drill-down.

Key Analytical Questions
•	How do Colorado hospitals vary in 30-day heart failure readmission performance?
•	Which hospitals perform better or worse than the state benchmark?
•	Is discharge volume associated with readmission outcomes?
•	What proportion of hospitals meet CMS reporting thresholds?
•	How is performance distributed statewide?

Data Source
CMS Care Compare – Hospital Readmissions (Heart Failure), 2020–2023
Public dataset published by the Centers for Medicare & Medicaid Services (CMS)

Tools & Technologies
Data Analysis
•	Python (Pandas, NumPy)
•	Jupyter Notebook
Visualization
•	Tableau Public
Version Control & Documentation
•	GitHub
•	Markdown

Data Preparation Overview (Python)
•	Imported and scoped CMS readmission data
•	Standardized and renamed analytical fields
•	Anonymized hospital identifiers
•	Converted CMS performance metrics to numeric format
•	Categorized hospitals by reporting eligibility and performance tier
•	Exported a clean, analysis-ready dataset for Tableau

Tableau Dashboard Components
•	Performance Ranking Bar Chart – Hospital-level excess readmission ratios vs state benchmark
•	Performance Tier Treemap – Distribution of hospitals by performance classification
•	CMS Reporting Eligibility Donut Chart – Methodological transparency
•	Performance Distribution Histogram – Clustering around CMS benchmark
•	Volume vs Performance Scatter Plot – Discharge volume vs outcomes
•	Interactive Filters – Reporting status, performance tier, and cross-chart filtering

Key Findings
•	Performance variation exists across Colorado hospitals
•	Higher discharge volume does not guarantee better performance
•	CMS reporting thresholds limit comparability for some facilities
•	Most hospitals cluster near expected performance, with few outliers

Skills Demonstrated
•	Healthcare quality measurement & CMS methodology
•	Python-based data cleaning and transformation
•	Performance metric engineering and categorization logic
•	Interactive Tableau dashboard design
•	End-to-end, reproducible analytics workflow

Future Enhancements
•	Multi-state comparison
•	Time-series trend analysis
•	Integration with HCAHPS patient experience metrics
•	Predictive readmission modeling

Contact
Interested in healthcare quality analytics or collaboration?
Connect with me on LinkedIn: Link
