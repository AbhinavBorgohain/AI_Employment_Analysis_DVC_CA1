# AI_Employment_Analysis_DVC_CA1

# Employment in AI, Data Science and Software Development

This project explores employment and annual pay across six selected occupations in the United States.

The main analysis uses BLS Occupational Employment and Wage Statistics data for May 2023. Additional data from May 2022 and May 2024 is used to explore employment trends.

## Selected occupations

- Computer and Information Research Scientists
- Database Architects
- Computer Programmers
- Software Developers
- Statisticians
- Data Scientists

## Visualisations

The notebook includes six types of visualisation:

1. Horizontal bar chart: compares national employment across the six occupations.
2. Box plot: compares state average annual pay across occupations.
3. Histogram: shows the distribution of state average annual pay for Data Scientists.
4. Heatmap: shows correlations between Data Scientist employment, average pay and employment concentration.
5. Scatter plot: compares Data Scientist employment and average pay across states and DC.
6. Line chart: compares national employment trends from 2022 to 2024, using an index where 2022 equals 100.

Each chart includes its objective, why the visualisation type was chosen and the main findings.

## Tools used

- Python
- Jupyter Notebook
- pandas
- Matplotlib
- Seaborn
- openpyxl

## How to run

1. Download `AI_Employment_Analysis.ipynb`.
2. Download the **All data** files for May 2022, May 2023 and May 2024 from the BLS page linked below.
3. Extract the Excel files and place these files in the same folder as the notebook:
   - `all_data_M_2022.xlsx`
   - `all_data_M_2023.xlsx`
   - `all_data_M_2024.xlsx`
4. Open the notebook in Jupyter with the required Python libraries installed.
5. Run the cells in order from top to bottom.


## Limitations

The figures cover whole occupations and do not identify how many people work specifically in AI.

The state pay charts compare area averages, not individual salaries. Missing values are excluded from the relevant charts.

The comparison across years is exploratory. Changes in employment estimates do not show that AI caused employment to rise or fall.

## Data source

US Bureau of Labor Statistics, Occupational Employment and Wage Statistics.

https://www.bls.gov/oes/tables.htm

Full references are included in the notebook.

## Author

Abhinav Borgohain
