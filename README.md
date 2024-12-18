# Term Paper: Gender Inequality in Russia

## Project Description
This repository contains materials, scripts, and final results for analyzing gender inequality in Russia. The project included data collection, calculations, and generation of comprehensive regional reports to assess the gender gap across Russian regions.

## Repository Structure
- **data_and_calculations.xlsx**  
  Contains raw data and calculations.  
  - The `Данные` sheet includes the collected raw data.  
  - The `Расчёты` sheet contains the computed gender inequality indices.  

- **subindex.xlsx**  
  A file with calculated subindices used for further analysis and generating final results.

- **page_html_template_2.txt**  
  An HTML template for generating detailed pages with results for each region. The template includes:
  - Region name.
  - General indicators and ranking position.
  - Detailed data on key categories: economic participation, education, health, and political opportunities.

- **solution_for_each_region.ipynb**  
  A Jupyter Notebook used to automate the generation of HTML files with results for each region. It includes logic for processing data and rendering the `page_html_template_2.txt` template.

- **result.pdf**  
  The final report, which includes regional rankings and detailed indices. The report provides insights into gender inequality across various categories, such as economic participation, education, health, and political opportunities.

## Workflow
1. **Data Collection and Processing:**  
   Raw data were collected and stored in `data_and_calculations.xlsx`. Calculations of indices were performed based on these data.

2. **Subindex Creation:**  
   Subindices were calculated in `subindex.xlsx`, providing aggregated data for visualization and detailed analysis.

3. **Regional Reports:**  
   Using Python and Jupyter Notebook (`solution_for_each_region.ipynb`), HTML pages for each region were generated from the `page_html_template_2.txt` template.

4. **Final Results Compilation:**  
   The results were compiled into `result.pdf`, which contains comprehensive rankings and analysis for each region.