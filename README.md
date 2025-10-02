# Ozone Exposure and Cardiovascular Disease Mortality Analysis

Machine learning analysis demonstrating that ozone exposure variability predicts county-level CVD mortality better than mean concentrations ($R^2=0.47$).

**Preprint**: [Ozone Exposure Variability Outweighs Mean Concentrations in Predicting Cardiovascular Disease Mortality](https://www.researchgate.net/publication/394321628_Ozone_Exposure_Variability_Outweighs_Mean_Concentrations_in_Predicting_Cardiovascular_Disease_Mortality_A_Machine_Learning_Analysis_of_US_Counties)

## Citation
If you use this code or data, please cite:

Godinez, Alejandro. 2025. Ozone Exposure Variability Outweighs Mean Concentrations in Predicting Cardiovascular Disease Mortality: A Machine Learning Analysis of US Counties. doi:10.13140/RG.2.2.29414.95048.

## Data Availability Notice

**Important**: The original CDC and EPA data sources were removed from public access in January 2025 following policy changes. 

All original datasets and intermediate files used in this analysis are preserved in this Google Drive folder: [[link](https://drive.google.com/drive/folders/1UBCjeFsMEX7O9wmGvbzYaAt10RFrIYvK?usp=sharing)]

- **For full reproduction**: Download the entire folder (190 GB) and run `data_preparation.ipynb`
- **To run analysis only**: Download just `merged_final_df.feather` (151 MB) and the model files, then run `random_forest.ipynb`

### Original Data Sources (archived):
- CDC Division for Heart Disease and Stroke Prevention Cardiovascular Disease Mortality (2001-2014)
- CDC Environmental Public Health Tracking Program Daily Ozone Data [link(https://data.cdc.gov/Environmental-Health-Toxicology/Daily-Census-Tract-Level-Ozone-Concentrations-2011/372p-dx3h/about_data)]
- US Census Population Estimates by County [Link(https://www2.census.gov/programs-surveys/popest/technical-documentation/file-layouts/2000-2008/co-est2008-alldata.pdf)]

The Google Drive serves as archive since some original sources are no longer accessible.

