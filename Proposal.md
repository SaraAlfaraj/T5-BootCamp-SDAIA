# Investigation of Saudi Arabia COVID-19 Cases (Oct 2020 - Oct 2021)
### By Sara Alfaraj | 3 Oct 2021

A key aspect of this study is to investigate COVID-19 cases in Saudi Arabia, in order to predict the most common factors that lead to increase COVID-19 number of cases.  

## Questions
- Are the different seasons and events (Summer, Winter, holidays, Eids...) affect the number of COVID-19 cases?
- Do the numbers of COVID-19 cases differ between big/main cities and small cities?
- What is the expected date of reaching zero cases? 
- Is the COVID-19 cases indicators expected to rise again after returning back to school ( at 31 Oct 2021)?

## Data Description 
- **The main data in this study obtained from The King Abdullah Petroleum Studies and Research Center [KAPSARC data portal](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-coronavirus-disease-covid-19-situation/export/?disjunctive.daily_cumulative&disjunctive.indicator&disjunctive.event&disjunctive.city_en&disjunctive.region_en), which gathered by [Ministr of Helth in Saudi Arabia](https://covid19.moh.gov.sa/).**
  - Include these fetures:
    - Number of Cases (Daily / Cumulative)
    - Case Indicators (Active, Mortalities, Critical ...)
    - Number of Cases 
    - Date
    - Events
    - City
    - Region
    - Day

  - Consists of 428346 row، related to 207 cities in Saudi Arabia.
  - Unit of measure: Persons.
  - Range of the dates: 1 Oct 2020 to 1 Oct 2021.

- **The prediction model will benefits from the above datasets.**

## Tools
- Jupyter Notebooks-Python (`Pandans`, `Numpy` , `Matplotlip` ...)

## MVP Goal
The minimum viable product (MVP) of this project will introduce a comparative analysis of COVID-19 cases within referred period, and discover the initial pattern of the dataset.
