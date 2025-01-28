# Conjoint Analysis of Consumer Preferences in Smartphones

This project explores consumer preferences for smartphone attributes using conjoint analysis.

## Project Contents
- **Report**: A comprehensive PDF report summarizing the analysis and findings.
- **Data**: The dataset used for the analysis.
- **R Script**: The R code used to perform the conjoint analysis.

## Files
1. `final_project_report.pdf`: The complete report detailing the methodology, analysis, and insights.
2. `conjoint_data.csv`: The dataset containing choice-based data for smartphone attributes. Key variables include:
   - **resp_id**: Unique respondent ID.
   - **Brand**: Smartphone brand (e.g., Xiaomi, Samsung, Apple).
   - **Price**: Price of the smartphone in dollars.
   - **ScreenSize**: Screen size in inches.
   - **BatteryLife**: Battery life in hours.
   - **CameraQuality**: Camera quality in megapixels.
   - **StorageCapacity**: Storage capacity in gigabytes.
   - **OperatingSystem**: Operating system (iOS or Android).
   - **Connectivity5G**: Whether the smartphone supports 5G (Yes or No).
   - **Choice**: Whether the alternative was selected (1 = Yes, 0 = No).

3. `conjoint_analysis.R`: The R script that performs:
   - Data preparation and cleaning.
   - Multinomial logit model implementation.
   - Mixed logit model analysis.
   - Sensitivity analysis and market share simulation.

