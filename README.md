# lse-dissertation-analysis
R code and replication materials for the MSc dissertation

## Project Description

This repository contains the complete R code and supplementary materials for the data analysis conducted in my MSc dissertation. The primary goal of this repository is to ensure the transparency and reproducibility of the research findings.

The analysis investigates the relationship between internet use, traditional gender role attitudes, and fertility intentions, using data from the Chinese General Social Survey (CGSS).

## Requirements

The analysis was performed using **R (version 4.3 or later)**. The following R packages are required to run the scripts. You can install them using the `install.packages("package_name")` command in R.

*   `haven`: For loading the Stata (`.dta`) data file.
*   `dplyr`: For data manipulation and wrangling.
*   `MASS`: For fitting negative binomial regression models.
*   `sandwich` & `lmtest`: For calculating robust standard errors.
*   `mediation`: For bootstrap-based mediation analysis.
*   `ggplot2`: For creating visualizations.
*   `janitor`: For creating frequency tables.

## Data Source

This study uses data from the **Chinese General Social Survey (CGSS) 2023**.

Due to data use agreements, the raw data file (`CGSS2023.dta`) is not included in this repository. Please download the dataset directly from the official source via the following link:

*   **CNSDA Official Download Page:** [https://www.cnsda.org/index.php?r=projects/view&id=11256439]

After downloading, please place the `CGSS2023.dta` file inside a folder named `data` within the project's root directory. The code assumes the following file path: `data/CGSS2023.dta`. You may need to adjust the file path in the first script (`01_data_preprocessing.R`) to match your local setup.

## Instructions for Replication

To ensure a successful replication of the analysis and results presented in the dissertation, please execute the R scripts in the following numerical order. Each script is designed to run sequentially and builds upon the outputs of the previous ones.
