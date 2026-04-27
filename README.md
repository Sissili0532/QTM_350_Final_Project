# Impact of Education and GDP on Adolescent Fertility

Project Description
This project investigates the relationship between economic prosperity and demographic outcomes across six diverse nations: Brazil, Switzerland, Italy, Malaysia, Niger, and India. Using data from the World Bank’s World Development Indicators (WDI) for the period of 2020–2024, the study explores how national wealth (GDP per capita) and educational attainment (Primary, Secondary, and Tertiary enrollment) influence adolescent fertility rates.. 

Using data from the World Bank’s World Development Indicators (WDI), the study 
explores how national wealth (GDP per capita) and educational attainment (Primary, 
Secondary, and Tertiary enrollment) influence adolescent fertility rates. 

## How to Reproduce the Analysis

1. Run data cleaning
Run the Jupyter Notebook: Final_Project_Data_Cleaning.ipynb

2. Generate figures and tables
Execute the following notebooks:
- descriptive_statistics.ipynb
- data_modeling.ipynb

3. Render the final report
quarto render "Economic Growth, Education, and Fertility: A Cross-National Analysis (2020-2024).qmd"

## Data Source
All indicators are sourced from the World Bank World Development Indicators (WDI) 
using the wbgapi Python package. The variables used are:

- NY.GDP.PCAP.CD: GDP per capita (current US$)
- SE.PRM.ENRR: Primary education enrollment (% gross)
- SE.SEC.ENRR: Secondary education enrollment (% gross)
- SE.TER.ENRR: Tertiary education enrollment (% gross)
- SP.ADO.TFRT: Adolescent fertility rate (births per 1,000 women ages 15-19)

The dataset is restricted to: Switzerland, Italy, Brazil, Malaysia, India, and Niger.

