# Literacy Rate Regression Analysis

Data Analysis 2 term project on student-teacher ratios, education indicators, and adult literacy rates.

## Project Overview

This project investigates whether student-teacher ratios are associated with adult literacy rates after controlling for broader education and economic factors. The analysis treats literacy as an educational outcome and asks whether classroom-resource indicators still matter once country-level development and schooling variables are included.

The repository includes the full notebook, rendered HTML output, final PDF report, raw data, and cleaned modeling data.

## Research Question

How much does the student-teacher ratio explain adult literacy rates when accounting for GDP per capita, public education spending, primary completion, and average years of schooling?

## Data

The project uses raw literacy and education data, then creates a cleaned dataset for regression analysis.

Files:

- `literacy_rate_raw_data.csv` - original raw dataset.
- `literacy_rate_cleaned_data.csv` - cleaned dataset used in the models.

Main variables include:

- Adult literacy rate
- Student-teacher ratio
- Government expenditure on education
- GDP per capita
- Primary education completion rate
- Average years of schooling

## Notebook Structure

- Introduction and motivation
- Data description
- Cleaning and preparation
- Model 1 baseline regression
- Model 2 with additional education controls
- Model 3 with economic controls
- Models 4 and 5 with fuller specifications
- Conclusion
- Appendices with supporting output

## Methods

The notebook uses multiple regression models to compare how the coefficient on student-teacher ratio changes as more controls are added. It also uses summary tables and visual diagnostics to interpret the strength and direction of the relationships.

## Files

- `Literacy_rate_term_project_artyom_ashigov.ipynb` - full analysis notebook.
- `Literacy_rate_term_project_artyom_ashigov.html` - rendered notebook output.
- `Literacy_rate_term_project_artyom_ashigov.pdf` - final report.
- `literacy_rate_raw_data.csv` - raw data.
- `literacy_rate_cleaned_data.csv` - cleaned modeling data.

## Tools

Python, pandas, numpy, seaborn, matplotlib, statsmodels, stargazer, and Jupyter Notebook.
