# Development-Control-Enforcement-in-Adansi-Asokwa
# Challenges and Effectiveness of Development Control Enforcement in Adansi Asokwa

📄 Full Report: [View Analysis](Development Control Enforcement in Adansi Asokwa.html)

## Overview
This project investigates the enforcement of development control regulations in Adansi Asokwa, Ghana, through a 2025 survey of 150 property owners, focusing on institutional challenges, measure effectiveness, and the role of support and engagement in compliance. Key barriers include low awareness of building regulations (2.7%) and information gaps (90.6% non-permit holders), leading to 70.1% non-compliance. While site inspections are moderately effective (70%), stop-work notices show low issuance (17.9%) and compliance (33.3%), with only 14.3% of unauthorized cases addressed. Institutional satisfaction (28.5%) and trust (18.9% high) significantly boost compliance (p<2.2e-16), yet sparse assistance (1.5%) limits impact. Findings advocate for awareness campaigns, capacity building, and participatory mechanisms to enhance regulatory adherence and curb unauthorized development in peri-urban areas.

## Dataset Summary
- **Source**: Primary survey data from property owners in Adansi Asokwa, Ghana (2025).
- **Sample Size**: 150 respondents.
- **Key Variables**: Demographics (age, gender, education, employment, residence duration); compliance indicators (building permits, reasons for non-compliance); enforcement measures (stop-work notices, site inspections, unauthorized observations); institutional factors (support satisfaction, trust, assistance, participation awareness).
- **Note**: Raw data is not included due to confidentiality. Please contact me for collaboration requests.


## Objectives
- Identify the key challenges affecting the enforcement of development control regulations in Adansi Asokwa.
- Evaluate the effectiveness of existing development control measures in preventing and addressing unauthorized development in Adansi Asokwa.
- Examine the extent to which institutional support and stakeholder engagement influence property owners’ compliance with development control policies in Adansi Asokwa.


## Methods
- Descriptive statistics (frequencies, percentages, means) and visualizations (bar plots, contingency tables) for profiling demographics, compliance, and perceptions.
- Inferential tests including Fisher's exact tests for associations (e.g., support satisfaction vs. permits) and Spearman's correlations for relationships (e.g., institutional presence vs. satisfaction).
- Logistic regression to model predictors of non-compliance and unauthorized observations, with odds ratios for interpretation.

## Key Findings
- Enforcement challenges stem from low building regulation awareness (2.7%) and information gaps (90.6% barrier), with 70.1% lacking permits; higher education (secondary/tertiary) reduces non-compliance (OR=0.138/0.051, p<0.05), while weak institutional presence (mean PPD rating 2.48) exacerbates issues.
- Control measures are ineffective, with 14% observing unauthorized buildings but only 14.3% addressed; site inspections are moderately effective (70%) and linked to observations (p<0.001, OR=7.94), but stop-work notices show low use (17.9%) and compliance (33.3%, p=0.005).
- Institutional support satisfaction (28.5%) strongly drives compliance (84.6% among satisfied, p<2.2e-16), as does trust in fairness (p=0.016); however, minimal assistance (1.5%) and low participation awareness (96.4%) limit engagement, with tertiary education boosting odds (OR=6.07, p=0.031).



## How to Reproduce the Analysis
### Requirements
- R (version 4.0 or higher)
- RStudio
- R packages: tidyverse, ggplot2, dplyr, broom, stats

### Steps
1. Clone this repository.
2. Open `analysis.Rmd` in RStudio.
3. Install required packages if not already installed (e.g., `install.packages(c("tidyverse", "broom"))`).
4. Knit the R Markdown file to generate the HTML report.
Data not included due to confidentiality. Please contact me for collaboration requests.

## Repository Structure
├── analysis.Rmd         # R Markdown source file  
├── analysis.html        # Knitted HTML report  
├── figures/             # Plots and visualizations  
├── README.md            # Project description  

## License / Citation
This project is for academic and research purposes. Please cite appropriately if referenced, e.g., Sei, Lawrence. (2025). Challenges and Effectiveness of Development Control Enforcement in Adansi Asokwa.
