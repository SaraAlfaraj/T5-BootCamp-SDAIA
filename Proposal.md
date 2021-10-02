# Investigation of Saudi Arabia COVID-19 Cases (Oct 2019 - Oct 2021)
### By Sara Alfaraj | 3 Oct 2021

Summary, brief overview of problem
History 
There is a growing body of literature that recognises the importance of …
Xs are one of the most widely used groups of Y and have been extensively used for ….
X can play an important role in addressing the issue of …
A key aspect of this study is …

## Questions
- Are the different seasons and events (summer, winter, holidays, Eids...) affect the number of COVID-19 cases?
- Do the numbers of COVID-19 cases differ between big/main cities and small cities?
- Is the COVID-19 cases indicators expected to rise again after returning back to school ( at 31 Oct 2021)?
- What is the expected date of reaching zero cases? 

## Data Description
- **The main data in this study obtained from [KAPSARC data portal](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-coronavirus-disease-covid-19-situation/export/?disjunctive.daily_cumulative&disjunctive.indicator&disjunctive.event&disjunctive.city_en&disjunctive.region_en), which gathered by [Ministr of Helth in Saudi Arabia](https://covid19.moh.gov.sa/).**
  - Include 7 fetures:
    - Number of Cases (Daily / Cumulative)
    - Case Indicators (Active, Mortalities, Critical ...)
    - Number of Cases 
    - Date
    - Events
    - City
    - Region
  - Consists of 428346 row، related to 207 cities in Saudi Arabia.
  - Unit of measure: Persons.
  - Range of the dates: 1 Oct 2019 to 1 Oct 2021.

- **The other -supported- dataset may use in this study to make a comparison with cases in overall the world, obtained from [Data World](https://data.world/zathompson/covid-19-case-counts-test).**
  - Include 13 fetures:
    - Case_Type (Confirmed, Deaths)
    - Number of Cases 
    - Difference
    - Date
    - Country_Region
    - Province_State
    - Admin2
    - Combined_Key
    - FIPS
    - Lat
    - Long
    - Table_Names
    - Prep_Flow_Runtime
  - Consists of 582660 row، related to 184 Country Region in overall th world. Saudi Arabia has 166 cases.
  - Range of the dates: 22 Jan 2020 to 4 Sept 2020.
- **The prediction model will benefits from the above datasets to**

## Tools
- Jupyter Notebooks-Python (`Pandans`, `Numpy` , `Matplotlip` ...)

## MVP Goal
The minimum viable product (MVP) of this project will introduce a comparative analysis of COVID-19 cases within referred period, and discover the initial pattern of the dataset.
