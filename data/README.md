# Dataset

**File:** `country_profile_variables.csv`
**Rows:** 229 countries/territories · **Columns:** 53 socio-economic indicators
**Source:** UN Statistics Division — *World Statistics Pocketbook*, distributed via [Kaggle](https://www.kaggle.com/datasets/sudalairajkumar/undata-country-profiles-variables) (mirror used here: [Data-Analytics-Project-Group/Visualizing-World-Economic-Trends](https://github.com/Data-Analytics-Project-Group/Visualizing-World-Economic-Trends)).

## Notes

- Missing values are encoded as `-99` in the raw file and are cleaned/converted to `NaN` in the notebook before analysis.
- After dropping rows with missing values in the six clustering features, **186 countries** remain in the final analysis.
- Six features are used for clustering:
  - GDP per capita (current US$)
  - Population density (per km², 2017)
  - Unemployment (% of labour force)
  - Fertility rate, total (live births per woman)
  - Urban population (% of total population)
  - Infant mortality rate (per 1000 live births)
