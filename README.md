# Percipitation Comparison

> This project compares the precipitation of Seattle, WA and Orlando, FL between January 1st 2018 - December 31st 2022.

---

## Project Overview

This project cleans and analyzes data to compare the precipitation at weather stations by the airport SEATAC in Seattle, WA and the airport MCO in Orlando, FL between January 1st 2018 and December 31st 2022. This project uses data downloaded from NOAA. The purpose is to determine which area recieves a larger amount of percipitation on average and to discover and display any other obvious trends. Findings TBD.

- **Objective:** This project compares the precipitation of Seattle, WA and Orlando, FL between January 1st 2018 - December 31st 2022.
- **Domain:** Weather/Environmental
- **Key Techniques:**  Regression, Statistical Tests of Significance

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** [Link to the data source](https://www.ncei.noaa.gov/cdo-web/search)
- **Description:** The data for this project was downloaded from the NOAA National Centers for Environmental Information. Climate Data Online Search. The data consists of daily summaries of precipitation data measured from two different NOAA weather stations: one in Seattle, WA and one in Orlando, FL.
- **License:** N/A

---

## Analysis
The entirety of the analysis is done in the Jupytr notebook Seattle_Weather.ipynb. The code in this notebook should be run in the order it is presented. The analysis consists of a progressive examination of the data through tables and graphs.

---

## Results
The results of the analysis shows that over the course of a year, Seattle typically experiences more days with precipitation, but Orlando experiences more total precipitation, measured in inches.

---

## Authors

- Kelsie McCall - [@keltisant](https://github.com/keltisant)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used - numpy, pandas, matplotlib, seaborn
- Seattle U Data 5100
