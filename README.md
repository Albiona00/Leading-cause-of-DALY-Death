# Leading-cause-of-DALY-Death

Overview

This project focuses on analyzing and understanding the leading causes of Disability-Adjusted Life Year (DALY) and death in different countries. The dataset contains information about various factors, including country details, causes, years, demographics, population, deaths, and DALY rates. The main objective of the analysis and processing of these data is to identify and understand the key factors that cause DALY (Disability-Adjusted Life Year) and death in different countries, over different years, and in various demographic groups, as well as to predict possible future occurrences of DALY and death. With this information, our aim is to identify the key factors to develop innovative solutions to mitigate or prevent their impact, while also raising public awareness of healthcare.


Dataset Description
The dataset includes the following columns:

- COUNTRY_CODE: Country code
- COUNTRY: Country name
- GHE_CAUSE_CODE: Cause code
- GHE_CAUSE_TYPE: Cause type
- GHE_CAUSE_TITLE: Cause title
- YEAR: Year
- SEX_CODE: Gender code
- AGEGROUP_CODE: Age group code
- POPULATION: Population
- DEATHS: Number of deaths
- DEATHS_RATE: Death rate
- DEATHS_100K: Deaths per 100,000 population
- DALY: Disability-Adjusted Life Year
- DALY_RATE: DALY rate
- DALY_100K: DALY per 100,000 population


Usage

Prerequisites: Make sure you have the required Python libraries installed. You can install them using:
pip install -r requirements.txt

Running the Code

Execute the Jupyter Notebook main.ipynb to view the analysis and visualization results.

Clone the repository to your local machine:

git clone https://github.com/Albiona00/Leading-cause-of-DALY-Death 

Navigate to the project directory:

cd Leading-Causes-of-DALY-Death

Install the necessary Python libraries:

pip install -r requirements.txt

Data Processing

Outliers - Data Quality (Normalization)

The project includes code for detecting and handling outliers using Z-scores. Outliers are visualized using box plots, and missing values, unique values, and duplicates are also analyzed.

Aggregation

The dataset is aggregated based on primary causes and countries to provide a summarized view of deaths and DALY.

Reduction of Dimensions

Columns related to rates are removed to reduce dimensionality.

Quality of Data

Column names are renamed for better clarity and understanding.

Visualization

Visualizations include box plots for potential outliers and bar plots for the top causes of death.

Execution of Changes

The dataset is saved after changes.

Additional Sections

The project includes additional code for binarization, subset selection, discretization, creation of attributes, and conversion of data types.

Contributors

Rina Shabani and Albiona Vukaj

Copyright
The data used in this analysis is sourced from World Health Organization (WHO).
Special thanks to the open-source community for providing valuable tools and resources used in this project.
