# 🚔 NYPD Officer Data Collection & Enrichment with Python
This project programmatically scrapes and consolidates public officer profile data from the NYPD Online Officer Profile Portal. Using a combination of <b> Python, REST API requests, and concurrent multithreading </b>, the goal is to build a full dataset of all active NYPD officers, enriched with detailed information such as:

- Arrests processed

- Disciplinary records

- Awards and recognitions

- Precinct/command assignment

- Self-reported ethnicity

Over 36,000 unique officers were processed using scalable, optimized scripts.




Files below are these. 

1. ```cis_4130_project_7.pdf```
(contains all writings of the project, and the step by step work for how I approached this project)

2. ```first_analysis.ipynb```
(the code written to do basic analysis and visualizations for the given data in jupyter notebook)

3. ```python_final_4.py```
(the code written to launch in an AWS EMR cluster and yield results)

5. ```test_for_emr.ipynb```
(the same code as above but incremental as its a Jupyter Notebook file)

4. ```Folder named visualizations```
(contains visualizations from the project)

 

## Insights and Conclusions
- The NYPD website provides separate endpoints for core data and additional tabs (e.g., recognitions, command info, etc.)

- Without parallelization, scraping over 36,000 officer profiles would take hours
  
## Future Work

Plans for this project include:

- Join this dataset with crime statistics for contextualized analysis

- Build a dashboard (e.g., with Streamlit or Dash) to explore patterns by precinct, race, or recognition count
