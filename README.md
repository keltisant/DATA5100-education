# Percipitation Comparison

> This project compares average ACT scores from 2016 to socioeconomic predictor variables to examine the relationship between average ACT score and general socioeconomic factors.

---

## Project Overview

This project compares average ACT score by school to socioeconomic predictor variables to examine the relationship between average ACT score and general socioeconomic factors. Average ACT scores use the EdGap data set described below. From the EdGap Data, we also examine unemployment rate, % adults with a college degree, % children in a married couple family, median household income, and % students eligible for free/reduced lunch. Further analysis is then conducted using the State of Washington Open Data Report Card Assessment to look at trends accross student demographic groups.

- **Objective:** This project compares average ACT scores from 2016 to socioeconomic predictor variables to examine the relationship between average ACT score and general socioeconomic factors.
- **Domain:** Education
- **Key Techniques:**  Pair Plots, Regression, Statistical Tests of Significance

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

- **Source:** 
[Link to primary EdGap source](https://www.edgap.org/#5/37.875/-96.987)
[Link to NCES source](https://nces.ed.gov/ccd/pubschuniv.asp)
[Link to WA Open Data source](https://data.wa.gov/education/Report-Card-Assessment-Data-2016-17-School-Year/5tvk-w2c5/about_data)
- **Description:** The data for this project comes from two sources. The primary data sourced is EdGap.org, and reports 2016 ACT and SAT scores and several socioeconomic characteristics of the school district. EdGap does not report that they have processed the data in any way, and it has been manually assembled from public release sources. The second data set is basic information about each school from the National Center for Education Statistics. The third data set is the State of Washington's Report Card Assessment for the 2016-2017 school year and contains student group information and data by student group on WA state test scores.

The data preparation for this analysis is done in the Jupytr Notebook education_data_preparation.ipynb. 
- **License:** N/A

---

## Analysis
The entirety of the analysis is done in the Jupytr notebook education_eda.ipynb. The code in this notebook should be run in the order it is presented. The analysis consists of a progressive examination of the data through tables and graphs.

---

## Results
The results of the analysis show...

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
